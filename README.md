# “Magazine” HTML template for Gozer
[Free CSS](https://www.free-css.com/free-css-templates/page215/magazine) “Magazine” template, adapted for the [Gozer](https://github.com/dannyvankooten/gozer) static generator.

This template is a basic version of the original. Pagination and support for tags is not included.

Live preview: [https://magazine-gozer.surge.sh](https://magazine-gozer.surge.sh)

![Template screenshot](https://raw.githubusercontent.com/htejera/magazine-gozer/main/screenshot1.webp)

![Template screenshot menu](https://raw.githubusercontent.com/htejera/magazine-gozer/main/screenshot2.webp)

# Installing and building

Gozer is a powerful static site generator written in Go. Follow these instructions to install Gozer and build your project.

## Prerequisites

Before installing Gozer, make sure you have Go installed. You need Go version 1.11 or later to use Gozer.

## Installing Gozer

To install Gozer, open a terminal and execute the following command:

```
go install github.com/dannyvankooten/gozer@latest
```

This command will download and install the latest version of Gozer; or download a precompiled binary from the [latest release](https://github.com/dannyvankooten/gozer/releases)

## Project Structure

After initializing your project, you'll find the following structure:

- `content/`: This directory contains your site's content, typically Markdown files.
- `public/`: This is where your site will be generated.

## Building

To build your site, navigate to your project's root directory in the terminal and run:

```
gozer build
```

This command processes your content files and generates your site in the `public/` directory.

## Serving the site locally

If you want to preview your site locally, you can serve it using Gozer by running:

```
gozer serve
```

This will start a local web server. By default, you can access your site by going to `http://localhost:8080` in your web browser.

For more information and advanced usage, refer to the [official Gozer documentation](https://github.com/dannyvankooten/gozer).

