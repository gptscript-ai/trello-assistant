# Trello API Tool

This project provides a set of tools to interact with the Trello API, making it easier to manage your Trello boards, cards, and organizations.

## Getting Started

### Prerequisites

To use this tool, you need to have the following credentials:

1. **Trello API Token**: You need to authenticate and generate a token using the following URL:
   ```
   https://trello.com/1/authorize?expiration=never&scope=read,write,account&response_type=token&key=aabf1a5f6af0a2e5c4c3807b4d3ccbc8
   ```
   You will be automatically prompted for this information when you are running the tool.

### Quick Start

```bash
gptscript github.com/gptscript-ai/trello-assistant
```

### Tools

The following tools are examples that available to interact with the Trello API:

- **post-cards**: Create new cards on a Trello board.
- **delete-cards-id**: Delete a card by its ID.
- **get-boards-id-cards**: Retrieve all cards on a specific board.
- **get-organizations-id-boards**: Retrieve all boards in a specific organization.
- **get-members-id-organizations**: Retrieve all organizations a member belongs to.

You can use all the API availiable in openapi.yaml as long as you know the operationID. For more details, check [here](https://docs.gptscript.ai/examples/api)

### Usage Examples

You can use these tools to perform various actions on your Trello account. Below are some examples:

#### Create a New Card

To create a new card on a Trello board, use the `post-cards` tool. You will need to provide the board ID and the card details.

#### Delete a Card

To delete a card by its ID, use the `delete-cards-id` tool. You will need to provide the card ID.

#### Retrieve All Cards on a Board

To retrieve all cards on a specific board, use the `get-boards-id-cards` tool. You will need to provide the board ID.

#### Retrieve All Boards in an Organization

To retrieve all boards in a specific organization, use the `get-organizations-id-boards` tool. You will need to provide the organization ID.

#### Retrieve All Organizations a Member Belongs To

To retrieve all organizations a member belongs to, use the `get-members-id-organizations` tool. You will need to provide the member ID. To get the current user's organizations, use "me" as the ID.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request.
