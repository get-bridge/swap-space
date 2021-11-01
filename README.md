# swap-space-action

![ci](https://github.com/get-bridge/swap-space-action/workflows/ci/badge.svg)
![tag](https://img.shields.io/github/v/tag/get-bridge/swap-space-action?sort=semver)

Typical usage of this action looks like this:

    - uses: get-bridge/swap-space-action@v1
      with:
        swap-size-mb: 4096

### inputs

Following inputs are used as `step.with` keys

| Name           | Required  | Default  | Type    | Description                         |
|----------------|-----------|----------|---------|-------------------------------------|
| `swap-size-mb` | false     | 4096     | Integer | Swap size in megabytes              |
