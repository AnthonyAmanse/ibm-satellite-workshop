# Pre-work

Prerequisites:

* IBM Cloud account
* IBM Cloud shell at [https://cloud.ibm.com/shell](https://cloud.ibm.com/shell)
  * this is a cloud environment where you can execute `ibmcloud` CLI commands and `kubectl`/`oc`
  * You'll need [IBM Cloud CLI](https://cloud.ibm.com/docs/openshift?topic=openshift-openshift-cli#cs_cli_install_steps) and [OpenShift CLI](https://cloud.ibm.com/docs/openshift?topic=openshift-openshift-cli#cli_oc) IF you choose to use your own environment.

Then for this workshop, you will need to use the tools provided below to get your IBM Cloud environment access to the workshop clusters and account.

#### Request access to Satellite environment

Click the link to go to the [Request Satellite environment ](https://grant-satellite-amol.mybluemix.net)tool. Lab key is **satellite.** Your IBMid is the email you used to register on [IBM Cloud](https://cloud.ibm.com/).

![](../.gitbook/assets/image%20%2817%29.png)

#### Request access to cluster number 1 \(dev\)

Click the link to go to the [Request Dev Cluster ](https://ddc-openshift-sat.mybluemix.net/)tool. Lab key is **oslab.** Your IBMid is the email you used to register on [IBM Cloud](https://cloud.ibm.com/).

#### Request access to cluster number 2 \(qa\)

Click the link to go to the [Request Dev Cluster ](https://ddc-satellite-qa.mybluemix.net/)tool. Lab key is **oslab.** Your IBMid is the email you used to register on [IBM Cloud](https://cloud.ibm.com/).

#### Request access to cluster number 3 \(prod\)

Click the link to go to the [Request Dev Cluster ](https://ddc-openshift-prod.mybluemix.net/)tool. Lab key is **oslab.** Your IBMid is the email you used to register on [IBM Cloud](https://cloud.ibm.com/).

![](../.gitbook/assets/image%20%2827%29.png)

To verify that you are able to access the environment and its clusters, login in IBM Cloud [https://cloud.ibm.com/](https://cloud.ibm.com/)

* You should see a new account is shared with you. Choose this to view the clusters you have.

![](../.gitbook/assets/image%20%2813%29.png)

* Then navigate to the **Resource list** using the left naviagtion bar. You should see **3 clusters** assigned to you.

![](../.gitbook/assets/image%20%285%29.png)

* Open the **OpenShift Console** on **each of the cluster in the new tabs**. You will use them in the later steps. To open the console, click on the cluster and click on the **OpenShift web console**

![](../.gitbook/assets/image%20%2822%29.png)

#### OpenShift Project/namespace assigned to you

In the OpenShift clusters, you will only have access to one project or namespace. To get this, go to the **OpenShift Console**. The first time you open it, you will be in the Developer view and you will see the project assigned to you. The screenshot below shows you an example:

![](../.gitbook/assets/image%20%2823%29.png)

{% hint style="info" %}
Take not of this **project name** as you will need to reference this later on.
{% endhint %}

You are now ready to proceed with the workshop.

