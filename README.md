# Analyze with CodeQL

Initializes CodeQL for SATS analyze of your code. Leverages the official [CodeQL: Init action](https://github.com/github/codeql-action/blob/main/init/action.yml) pre-configured specifically for the majority.

> This action is part of the Codebelt ecosystem and ensures a consistent way of: 
> 
> - Defining your CI/CD pipeline 
> - Structuring your repository
> - Keeping your codebase small and feasible
> - Writing clean and maintainable code
> - Deploying your code to different environments
> - Automating as much as possible
>
> A paved path to excel as a DevSecOps Engineer.

## Usage

To use this action in your GitHub repository, you can follow these steps:

```yaml
uses: codebeltnet/codeql-scan@main
```

### Inputs

```yaml
with:
  # A comma-separated list of CodeQL languages to analyze.
  languages: 'csharp'
```

### Outputs

This action has no outputs.

## Examples

### Prepare CodeQL

```yaml
steps:
  - name: Prepare CodeQL SAST Analysis
    uses: codebeltnet/codeql-scan@main
```

## Contributing to Analyze with CodeQL

Contributions are welcome! 
Feel free to submit issues, feature requests, or pull requests to help improve this action.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
