Code example
============
The below is some example code. 

#. Enter the commands below, one at a time. Remember, :console:`>` shows the prompt (i.e. where to enter the commands). It is displayed by PowerShell, you don't need to enter it yourself. These commands install the software we'll use.

   - You may be asked to enter some information during the installation, and some graphical items may be displayed. Enter any needed information and press Enter to proceed.
   - Let each command complete before moving on to the next.
   
   .. prompt::
      :language: powershell

      winget install -e --id Microsoft.VisualStudioCode
      winget install -e --id Docker.DockerDesktop
      winget install -e --id Git.Git
      wsl --install

#. You will be asked to reboot the computer.

   .. admonition:: Aside
      :class: dropdown

      This uses the `Windows Subsystem for Linux (WSL) <https://docs.microsoft.com/en-us/windows/wsl/about>`_ backend, which is available on Windows Home and Windows Pro. If you are running Windows Pro, you can also use the `Hyper-V <https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/about/>`_ backend. Both work equally well for this course, but WSL is preferred.
