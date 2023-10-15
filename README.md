
# Woodpecker's LlamaIndex Example

This project is a simple yet fully functional example of the LlamaIndex implementation to allow natural language queries in a GitHub repository. More information can be found in this Medium article [Introducing LlamaIndex](https://medium.com/@woodpecker2000/introducing-llamaindex-169bbf475a94).

# Execution Steps

1. Fork and clone this repository
2. Rename the `env.example` file to `.env` and update tokens appropriately:
   * A GitHub personal access token generated on the [GitHub tokens page](https://github.com/settings/tokens/new). The token should have `repo`and `read:org` scopes.
   * An OpenAI key generated on the [OpenAI account page](https://platform.openai.com/account/api-keys).
3. Proceed with the following commands to run the project code:

```
$ poetry shell
$ python ingest.py
$ python query.py
```