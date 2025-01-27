The following server configuration values have been added

- ``esbonio.server.enableDevTools``: Enable integration with `lsp-devtools <https://github.com/swyddfa/lsp-devtools>`__ for the language server itself.

The following sphinx configuration values have been added

- ``esbonio.sphinx.buildCommand``: Set the ``sphinx-build`` command to use when invoking the Sphinx subprocess

- ``esbonio.sphinx.pythonCommand``: By default, the extension will attempt to reuse the Python environment you have configured in the Python extension when invoking Sphinx.
  This option can be used to override this behavior.

- ``esbonio.sphinx.cwd``: The working directory from which to launch the Sphinx process

- ``esbonio.sphinx.envPassthrough``: A list of envrionment variables to pass through to the Sphinx process.

- ``esbonio.sphinx.enableDevTools``: Enable integration with `lsp-devtools <https://github.com/swyddfa/lsp-devtools>`__ for the sphinx process

  - ``esbonio.sphinx.pythonPath``: Used to override the Python packages (typically ``esbonio.sphinx_agent``) that are injected into the Sphinx environment

The following preview related options have been added

- ``esbonio.sphinx.enableSyncScrolling``: Enable support for syncronised scrolling between the editor and preview pane
- ``esbonio.preview.bind``: Set the network interface that the preview server binds to
- ``esbonio.preview.httpPort``: Set the port number the HTTP server binds to
- ``esbonio.preview.wsPort``: Set the port number the WebSocket server binds to
