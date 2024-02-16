<div align="center">
    <a href="https://empress.eco/app/files/">
        <img src="https://avatars.githubusercontent.com/u/46308912?s=96&v=4" height="50">
    </a>
    <h2>Empress Files</h2>
    <p align="center">
        <p>Simple, Secure, File Sharing.</p>
    </p>

[![CI](https://github.com/frappe/erpnext/actions/workflows/server-tests-mariadb.yml/badge.svg?event=schedule)](https://github.com/frappe/erpnext/actions/workflows/server-tests-mariadb.yml)
[![Open Source Helpers](https://www.codetriage.com/frappe/erpnext/badges/users.svg)](https://www.codetriage.com/frappe/erpnext)
[![codecov](https://codecov.io/gh/frappe/erpnext/branch/develop/graph/badge.svg?token=0TwvyUg3I5)](https://codecov.io/gh/frappe/erpnext)
[![docker pulls](https://img.shields.io/docker/pulls/frappe/erpnext-worker.svg)](https://hub.docker.com/r/frappe/erpnext-worker)

[https://empress.eco/app/files/](https://empress.eco/app/files/)

</div>


## Welcome to Empress Files

Empress Files is a versatile document sharing and management solution designed to facilitate secure and efficient file storage and collaboration across multiple platforms.

## Table of Contents

- [Welcome to Empress Files](#welcome-to-empress-files)
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)
- [Support](#support)

## Installation

To set up Empress Files locally, execute the following commands:

```bash
git clone https://github.com/frappe/drive.git
```

```bash
cd drive
```

```bash
bench get-app drive
```

```bash
bench new-site drive.site
```

```bash
bench --site drive.site add-to-hosts
```

```bash
bench --site drive.site install-app drive
```

```bash
bench start
```

```bash
cd apps/drive && yarn dev
```

Then, open http://drive.site:8000/drive in your browser to access the app.

## Usage

Use Empress Files to manage your files on the cloud. With features like file preview, comments, favorites, and a robust search bar, you can easily store, access, and collaborate on documents.

## Features

* Upload and store files on multiple platforms.
* List or Grid view with customizable sorting.
* Previews for images, videos, PDFs, and more.
* File and folder sharing with permission management.
* Commenting on shared files.
* Favorites for quick access.
* Search functionality for easy file retrieval.
* Real-time collaborative document editing.

## Contributing

Contributions are welcome! Here's how you can contribute:

* Star the repository.
* Report issues or suggest features by filing an issue.
* Follow the contribution guidelines as outlined:

```bash
git checkout -b feature/AmazingFeature
```
```bash
git commit -m 'Add some AmazingFeature'
```
```bash
git push origin feature/AmazingFeature
```

Then open a pull request for discussion and review.

## License
Empress Files is licensed under the GNU Affero General Public License v3.0.

## Support

If you need help or want to discuss the project, please reach out through the issue tracker or contact us at support@example.com.

Note: Empress Files is currently in beta. We welcome your feedback and contributions but please be aware of potential breaking changes.

We extend our gratitude to all the contributors and resources that have made this project possible.