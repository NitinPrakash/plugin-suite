# Plugin Suite For WP ( Work In Progress )

Plugin Suite 1.0 is a basic framework for WordPress plugin development, providing a foundation for building extensible and feature-rich plugins. The framework follows a modular structure, allowing developers to easily extend its functionality and integrate with various WordPress features.

## Features:
- **BasePlugin Class**: A base class that serves as the foundation for all plugins. It provides common functionality such as initialization, activation, deactivation, and uninstallation hooks.
- **Admin Class**: Provides functionality specific to the WordPress admin area, allowing developers to create custom admin pages, menus, and settings.
- **Settings Class**: Offers utilities for managing plugin settings and options.
- **RestAPI Class**: Facilitates integration with the WordPress REST API, enabling developers to expose custom endpoints and handle API requests.

## Usage:
To use Plugin Suite 1.0 in your WordPress plugin development:
1. Include the framework in your project.
2. Extend the `BasePlugin` class and implement your plugin's specific functionality.
3. Optionally, utilize the `Admin`, `Settings`, and `RestAPI` classes for additional features and integrations.

Plugin Suite 1.0 simplifies WordPress plugin development by providing a structured framework with essential components for building powerful and flexible plugins.

