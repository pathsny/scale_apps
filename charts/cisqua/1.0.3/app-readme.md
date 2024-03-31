# Cisqua

Cisqua is a powerful and intuitive AniDB client and local anime library management tool. With Cisqua, users can effortlessly search, organize, and track their anime series with data directly sourced from AniDB, ensuring a rich and up-to-date repository of anime information.

## Key Features

- **AniDB Integration**: Seamlessly search for and retrieve detailed information on anime series, characters, and creators.
- **Library Management**: Organize your anime collection with comprehensive library management tools.
- **User-friendly Interface**: A clean and intuitive interface designed for ease of use, allowing for quick navigation and management of your anime library.
- **Customizable Settings**: Tailor Cisqua to fit your personal preferences with customizable settings.

## Quick Start

To get started with Cisqua in your Kubernetes cluster, you can deploy it using the provided Helm chart. This chart is specifically designed for Truenas Scale.

To test it locally, you need a local deployment of Kubernetes (such as the one provided by Docker Desktop.)
```
  helm repo add scale-apps https://github.com/pathsny/scale-apps
  helm install cisqua scale-apps/cisqua
  kubectl port-forward svc/cisqua 4567:4567
```

Then, navigate to http://localhost:4567 in your web browser.

## Contributing
Contributions to Cisqua are always welcome, whether it's reporting issues, submitting improvements, or adding new features. Please visit [Cisqua's GitHub repository](https://github.com/pathsny/cisqua) to get involved.

## Support
If you encounter any issues or require assistance, please open an issue on the [GitHub issue tracker](https://github.com/pathsny/cisqua/issues).

## License
Cisqua is open-sourced software licensed under the [MIT license](https://opensource.org/license/mit).


