
# Install Intel OpenVINO to Red Hat OpenShift Data Science 

Please continue onto [tutorial examples](02_examples.md) if OpenVINO is already enabled in Red Hat OpenShift Data Science.

**Install OpenVINO one of two ways:**
* [From the Red Hat OpenShift Data Science Dashboard - (preferred)](#install-using-red-hat-openshift-data-science-dashboard)
* [OperatorHub](#install-using-operatorhub-from-the-openshift-dedicated-dashboard)
<!-- or you are using the sandbox cluster (future) -->

## Install using Red Hat OpenShift Data Science Dashboard

Installing integrated partner software is extremely easy within the Red Hat OpenShift Data Science dashboard. 

![rhods-dashboard-explore](./assets/img/install/rhods-dashboard-explore.png)

Simply navigate to the "Explore" tab on the left and research components you'd like to add to your environment. 

![openvino-get-started](./assets/img/install/openvino-get-started.png)

Clicking the OpenVINO tile will open a panel on the right side of your screen so you can learn more about OpenVINO's benefits. 
There's a section called "Installing OpenVINO Toolkit".
Follow the links to subscribe and install using Red Hat Marketplace. 

![openvino-rhm](./assets/img/install/openvino-rhm.png)
Above is the current product listing in Red Hat Marketplace. 
The self-guided installation process only takes a few minutes after selecting "Purchase" or "Free trial". 

<!-- get some docs to link out to this piece --> 

## Install using OperatorHub from the OpenShift Dedicated Dashboard

This option is available to `cluster-admin`s within the OpenShift Dedicated environment.

Search for "OpenVINO" after navigating to OperatorHub underneath the Operators tab on the left-hand side of your screen. 

![openvino-operatorhub](./assets/img/install/openvino-operatorhub.png)

You still have the option to install using Red Hat Marketplace, or you can install the second tab directly. 
The same operator is installed either way. 
A panel will open on the right side of your screen.
Click install and follow instructions to install to your cluster.


## Installation complete. Let's get started! 

The Intel OpenVINO includes documentation and other resources directly within the Red Hat OpenShift Data Science dashboard.

![openvino-resources](./assets/img/install/openvino-resources.png)

Simply navigate to the Resources tab and search "openvino" to find resources included by the OpenVINO team.

![rhods-dashboard-enabled](./assets/img/install/rhods-dashboard-enabled.png)

Now that you have Intel OpenVINO installed, navigate back to the "Enabled" tab within Red Hat OpenShift Data Science. 
You will see an OpenVINO tile displayed alongside your other components.

Intel OpenVINO offers an embedded notebook experience. 
We access their software through Jupyter Notebooks.
To get started, please click "Launch application" on the JupyterHub tile.

![jupyter-launcher](./assets/img/install/jupyter-launcher.png) 

"Launch application" opens the notebook spawner. 
Simply select "OpenVINO Toolkit" from the list of notebook images.
These embedded notebooks are provided by Red Hat OpenShift Data Science and enabled partner components. 

Next, select an appropriate container size from the "Deployment size" drop down. 
You will see a list of pre-configured image sizes.
These, of course, are customizable. 
You also have the ability to add environment variables. 
You can add key-value pairs by clicking "Add more variables". 
This is particularly useful when passing moderately sensitive information, like host names, etc., into your environment. 

Lastly, click "Start Server" when you're ready to launch your notebook!

Continue to the next step: [try some OpenVINO examples](02_examples.md)

## Navigation 

* [Welcome - Intel OpenVINO Tutorials Red Hat OpenShift Data Science](00_index.md)
* [Install OpenVINO to Red Hat OpenShift Data Science](01_install.md) - **(you are here)**
* [OpenVINO Examples](02_examples.md)
