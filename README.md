# modal_from_actions

Run [modal](https://modal.com/) from GitHub Actions

## How to do
- Create a modal account
- Log in and generate a new token [here](https://modal.com/settings/tokens). You will see the command somthing like `modal token set --token-id abc12345 --token-secret def6789`. Remeber the token-id and token-secret.
- In your GitHub repository, go to Settings -> Security -> Secrets and variables -> actions. Create new repository secret, `MODAL_TOKEN_ID` and `MODAL_TOKEN_SECRET`. Set your token-id and token-secret.
- Now you can use modal from actions. See [here](.github/workflows/modal.yml) for an example.
