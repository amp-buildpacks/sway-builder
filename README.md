# `ghcr.io/amp-buildpacks/sway-builder`

A Cloud Native Buildpacks (CNB) builder with Paketo stacks (Jammy Jellyfish) and sway-builder

## Usage

To create the builder, just run

```shell
pack builder create <published-to>/sway-builder --config builder.toml
```

For example

```shell
pack builder create amp-buildpacks/sway-builder --config builder.toml
```

You can then build an app with it using 

```shell
pack build <image-name> --builder <published-to>/sway-builder
```

## Contributing

If anything feels off, or if you feel that some functionality is missing, please
check out the [contributing
page](https://docs.amphitheatre.app/contributing/). There you will find
instructions for sharing your feedback, building the tool locally, and
submitting pull requests to the project.

## License

Copyright (c) The Amphitheatre Authors. All rights reserved.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

      https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

## Credits

Heavily inspired by https://github.com/paketo-buildpacks/builder-jammy-tiny
