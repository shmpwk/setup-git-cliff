# setup-git-cliff

## Usage

```sh
jobs:
  test:
    runs-on: ubuntu-latest
    steps:
      - name: Check out repository
        uses: actions/checkout@v2

      - name: Set up git-cliff
        uses: ./

      - name: Run git-cliff
        run: |
          git cliff
```

## Inputs

| Name    | Required | Description                 |
| ------- | -------- | --------------------------- |
| version | false    | The version of `git-cliff`. |

## Outputs

None.
