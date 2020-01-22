---

copyright:
  years: 2020
lastupdated: "2020-01-21"

keywords: IBM Cloud Shell, beta, limitations, known issues, beta limitations

subcollection: cloud-shell

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:table: .aria-labeledby="caption"}
{:codeblock: .codeblock}
{:tip: .tip}
{:important: .important}
{:note: .note}

# Known issues and limitations
{: #issues-limitations}

{{site.data.keyword.cloud-shell_full}} (Beta) includes the following known issues and limitations that might impact your experience.
{: shortdesc}

## Known issues
{: #known-issues}

* Your {{site.data.keyword.cloud-shell_short}} workspace includes 500 MB of temporary storage. If you use all of your storage space, your connection to {{site.data.keyword.cloud-shell_short}} lost. To access {{site.data.keyword.cloud-shell_short}}, you must restart it, which removes all of your files.
* You can use the {{site.data.keyword.dev_cli_notm}} CLI plug-in (`ibmcloud dev`) to work with cloud-based resources such as pipelines and toolchains. However, it can't be used to work locally, such as to build, test, or run apps.

## Limitations
{: #limitations}

* {{site.data.keyword.cloud-shell_notm}} runs in the Dallas (`us-south`) region only. You can access resources in any region.
* Usage is limited to 4 hours of continuous use or 30 hours of weekly use. For more information, see [Tracking your usage](/docs/cloud-shell?topic=cloud-shell-shell-ui#usage-limit).
* As a beta service, {{site.data.keyword.cloud-shell_notm}} is not for production use. For a complete list of terms and notices, see [{{site.data.keyword.cloud_notm}} Terms and Notices](/docs/overview?topic=overview-terms).