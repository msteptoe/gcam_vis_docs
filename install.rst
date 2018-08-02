Installation
==================

1.  Download and install `Node.js <https://nodejs.org>`_ (Node.js version **>= 8.9.0**) for your platform.
    You can check if you already have an existing installation using the following command into
    your Terminal window, Command Prompt, or Node.js Command Prompt:

    ..  code-block:: bash

        node -v

    *   On all platforms, allow the installer to install with ``Add to PATH`` enabled
        unless you plan to add Node.js to your ``PATH`` on your own. To do so on your
        you can follow the process similar to below for the ``Node.js`` directory
        (Windows -> C:/Program Files/nodejs/ || macOS and Linux -> /opt/local/bin).

2.  Download and install `Anaconda 5 <https://www.anaconda.com/download>`_
    (**Python 2.7** version) for your platform.
    You can check if you already have an existing installation using the following command into
    your Terminal window, Command Prompt, or Anaconda Prompt:

    ..  code-block:: bash

        conda list

    *   On Windows, you can use the Anaconda Prompt from the Start menu to open a
        command prompt configured for your Anaconda installation. Alternatively, you can
        allow the Anaconda installer to set the required ``PATH`` elements (or set them yourself)
        to use Anaconda from a standard Windows command prompt. If you do this
        manually, add both the ``Anaconda2`` directory (typically in C:/Users/*your name*/Anaconda2)
        and the ``Anaconda2/Scripts`` directory below that, to your ``PATH``.

    *   On macOS and Linux (assuming you installed Anaconda in your home directory) make sure
        ``$HOME/anaconda2`` and ``$HOME/anaconda2/bin`` are in your ``PATH``. You can add these to your
        ``PATH`` using by adding this command to your shell's startup file:

        ..  code-block:: bash

            # Adjust as needed if Anaconda is installed somewhere other than $HOME
            PATH="$HOME/anaconda2:$HOME/anaconda2/bin"

3.  Clone the gcam_vis source code from the code repository (https://github.com/msteptoe/gcam_vis)
    to create a local copy. You can then install the necessary dependencies ``gcam_vis`` using npm.

        ..  code-block:: bash

            # Clone the git repository
            git clone https://github.com/msteptoe/gcam_vis.git
            cd gcam_vis

            # Install gcam_vis dependencies
            npm install