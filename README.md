# Salesforce LWC PokeAPI Integration

This repository contains a Salesforce Lightning Web Component (LWC) that interfaces with the PokeAPI to fetch and display a list of Pokémon.

After finishing the development, create a PR to make an evaluation. 

## Prerequisites
1. Salesforce DX
2. Salesforce Org
3. Git

## Installation

Follow these steps to set up the project:

1. Clone the repository:
```
git clone https://pokeapi.co/api/v2/pokemon/
```
2. Authorize your Salesforce org and provide it with an alias:
```
sfdx force:auth:web:login -d -a <your-alias>
```
3. Push the code to your Salesforce org:
```
sfdx force:source:push
```
4. Open your Salesforce org:
```
sfdx force:org:open
```
After performing these steps, you should see the LWC component ready to be added to a Lightning page.

## Usage

1. Navigate to a Lightning page where you want to display the Pokémon list.
2. Click 'Edit Page'.
3. From the Lightning components, find your custom component and drag it onto the page.
4. Click 'Save' and then 'Activate' to enable the page.

You should now see a list of Pokémon displayed on the page.

## Testing
If possible add Jest testing.

## Future Enhancements

- Add pagination to display more Pokémon.
- Add a search function to filter Pokémon by name.
- Display additional Pokémon details in a modal when a Pokémon name is clicked.
