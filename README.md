# swap-space-action

![ci](https://github.com/get-bridge/swap-space-action/workflows/ci/badge.svg)
![tag](https://img.shields.io/github/v/tag/get-bridge/swap-space-action?sort=semver)

In some cases you may need to make the swap space larger than the runners default (4096)

Typical usage of this action looks like this:

    - uses: get-bridge/swap-space-action@v1
      with:
        swap-size-mb: 8192

### inputs

Following inputs are used as `step.with` keys

| Name           | Required  | Default  | Type    | Description                         |
|----------------|-----------|----------|---------|-------------------------------------|
| `swap-size-mb` | false     | 8192     | Integer | Swap size in megabytes              |
