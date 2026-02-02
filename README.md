# University of Arizona GenAI Platform Documents
This repo is for documentation of the U of A GenAI platform. The docs website is currently being served through Github at https://ua-ai2s.github.io/genAI_documentation


## License

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

## About This Site

This documentation website is built with [Zensical](https://zensical.co/), the next-generation static site generator by the Material for MkDocs team. Zensical provides enhanced performance, better plugin support, and a modern configuration approach using TOML.

## Clone to your local machine for editing the content

To view the website locally, you will need to have Python and `pip` installed.

1.  Clone the repository:
    ```bash
    git clone https://github.com/UA-AI2S/genAI_documentation.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd genAI_documentation.git
    ```
3.  Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

### Development Server

To start the local development server with live reload:

```bash
zensical serve
```

Open your web browser and navigate to `http://127.0.0.1:8000` to view the website. Changes to markdown files will automatically refresh the browser.

### Building the Site

To build the static site for production:

```bash
zensical build
```

The generated site will be in the `site/` directory.

## Configuration

The site configuration is in `zensical.toml`. This file defines:
- Site metadata and theme settings
- Navigation structure
- Markdown extensions
- Plugin configurations

