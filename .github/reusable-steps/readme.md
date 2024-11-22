# Short description of this Composite Action
description: Template repository of composite GitHub Action

## About

This action runs setup for SDK and maven setting.

## Usage

### Setup Java and Maven

```yml
      - name: Set up JDK 17 and Maven
        uses: ./github/reusable-steps
        with:
          github_actor: ${{ inputs.github_actor }}
          access_token: ${{ inputs.access_token }}
```

## Support

@stchoupkoua/pipeline-test

## Copyright

Copyright (C) 2024 SkyEngPro
