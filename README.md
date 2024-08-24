# Hexya Web Module

[![Build Status](https://travis-ci.com/hexya-addons/web.svg?branch=master)](https://travis-ci.com/hexya-addons/web)  
[![Go Report Card](https://goreportcard.com/badge/hexya-addons/web)](https://goreportcard.com/report/hexya-addons/web)  
[![License: LGPL v3](https://img.shields.io/badge/License-LGPL%20v3-blue.svg)](https://www.gnu.org/licenses/lgpl-3.0)

## Overview

The Hexya Web module provides the core functionalities for the Hexya Web Client. It handles the user interface and interactions with the backend, enabling a seamless experience for users accessing Hexya ERP through a web browser.

## Features

- **UI Components**: Core components and utilities for rendering the web interface.
- **Controllers**: Manages client-server communication and user interactions.
- **Routing**: Handles navigation and URL management within the web client.

## Installation

To integrate this module:

1. Add it to your Hexya project’s `go.mod`:
   ```go
   require github.com/hexya-addons/web v0.1.7
   ```
2. Import it in your main setup:
   ```go
   import _ "github.com/hexya-addons/web"
   ```

## Directory Structure

- **Go Source Files**: Core logic for web client functionality.
- **Resources**: XML files for configuring views, actions, and menus.
- **Static Assets**: Images and other assets used in the web client.

## Running Tests

Use the `run_tests.sh` script to execute the test suite:

```bash
./run_tests.sh
```

Ensure that your environment is configured correctly.

## Contributing

Contributions are welcome! Follow the [contribution guidelines](https://github.com/hexya-erp/hexya/blob/master/doc/contribution.adoc) for more information.

## License

This module is licensed under the LGPL v3.0. See the [LICENSE](https://www.gnu.org/licenses/lgpl-3.0) file for details.