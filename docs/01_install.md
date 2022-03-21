
# Install Intel OpenVINO to Red Hat OpenShift Data Science 

Please continue onto [tutorial examples](examples.md) if OpenVINO is already enabled in Red Hat OpenShift Data Science.

<!-- or you are using the sandbox cluster (future) -->

## Install using Red Hat OpenShift Data Science Dashboard (Preferred)

Installing integrated partner software is extremely easy within the Red Hat OpenShift Data Science dashboard. 

![rhods-dashboard-explore](./assets/img/rhods-dashboard-explore.png)

Simply navigate to the "Explore" tab on the left and research components you'd like to add to your environment. 

![openvino-get-started](./assets/img/openvino-get-started.png)

Clicking the OpenVINO tile will open a panel on the right side of your screen so you can learn more about OpenVINO's benefits. 
There's a section called "Installing OpenVINO Toolkit".
Follow the links to subscribe and install using Red Hat Marketplace. 

![openvino-rhm](./assets/img/openvino-rhm.png)
Above is the current product listing in Red Hat Marketplace. 
The self-guided installation process only takes a few minutes after selecting "Purchase" or "Free trial". 

<!-- get some docs to link out to this piece --> 

## Install using OperatorHub from the OpenShift Dedicated Dashboard

This option is available to `cluster-admin`s within the OpenShift Dedicated environment.

Search for "OpenVINO" after navigating to OperatorHub underneath the Operators tab on the left-hand side of your screen. 

![openvino-operatorhub](./assets/img/openvino-operatorhub.png)

You still have the option to install using Red Hat Marketplace, or you can install the second tab directly. 
The same operator is installed either way. 
A panel will open on the right side of your screen.
Click install and follow instructions to install to your cluster.


## Installation complete. Let's get started! 

![rhods-dashboard-enabled](./assets/img/rhods-dashboard-enabled.png)

Now that you have Intel OpenVINO installed, navigate back to the "Enabled" tab within Red Hat OpenShift Data Science. 
You will see an OpenVINO tile displayed alongside your other components.

Intel OpenVINO offers an embedded notebook experience. 
We access their software through Jupyter Notebooks.
To get started, please click "Launch application" on the JupyterHub tile.

Next steps: [try some OpenVINO examples](examples.md)