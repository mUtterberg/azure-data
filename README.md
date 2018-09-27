# azure-data

Dabbling in Azure.

My initial impression is that the look is very old-school, somewhat ugly, and clearly Microsoft. However, I absolutely love that there is a clear "All Resources" tab, which is not easily accessible on AWS and GCP.

GCP makes it exceptionally convoluted to identify all resources by displaying them only by project, with additional navigating necessary to view all IAM roles/permissions (again, separated by project). The resources information for each project is displayed as a minimal summary card, only listing major GCP product type and number of instances, which is frustrating from a project clean-up perspective. For example, mine lists instances of App Engine, Compute Engine, and Cloud Storage. Viewing details of a VM instance gives some helpful information, but the instance link to Network Details - the only link that looks like it might give DNS insight - links to VPC Network information only. I'd need to navigate directly to a sub-tab of Network Services to find DNS records associated with those active resources - there is no way to navigate there from the instance details page. So GCP makes it unreasonably complicated to manage the resources you create.

### Tasks:

* [Get started with Hadoop and Hive in Azure HDInsight - Resource Manager template](https://docs.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-linux-tutorial-get-started) - 10 minute read

  * Template and parameters from above are [available for download on GitHub](https://github.com/Azure/azure-quickstart-templates/tree/master/101-hdinsight-linux-ssh-password), as are [many other Azure quickstart template resource files](https://github.com/Azure/azure-quickstart-templates).

* Chart out product analogies between Azure and AWS/GCP for reference
