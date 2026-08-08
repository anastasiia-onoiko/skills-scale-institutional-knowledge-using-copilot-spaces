# Create PR workflow: usage

This workflow is intended to be run manually from the Actions tab after it is committed.

1. Add the file `.github/workflows/create-pr-personas.yml` to the repository (preferably commit it to the `add-personas-and-process-improvements` branch you already created).
2. From the repository Actions page, select "Create PR for personas updates" and click "Run workflow".
3. The workflow will create a pull request from `add-personas-and-process-improvements` into the default branch (`main`) and request review from `@anastasiia-onoiko`.

Notes:
- No secrets required; the workflow uses the built-in `GITHUB_TOKEN`.
- If your default branch is not `main`, edit the `base:` value in the workflow before running.
