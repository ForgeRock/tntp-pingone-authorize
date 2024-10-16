<!--
 * This code is to be used exclusively in connection with Ping Identity Corporation software or services. Ping Identity Corporation only offers such software or services to legal entities who have entered into a binding license agreement with Ping Identity Corporation.
 *
 * Copyright 2024 Ping Identity Corporation. All Rights Reserved
-->

# PingOne Authorize Node

The PingOne Authorize Node sends a decision request to a specified decision endpoint in your PingOne Authorize environment. These authorizations include:

* [Policy Decision Authorization](https://apidocs.pingidentity.com/pingone/platform/v1/api/#post-evaluate-a-decision-request)
* [Individual Requests](https://apidocs.pingidentity.com/pingauthorize/authorization-policy-decision/v1/api/guide/#post-authorize-client-with-individual-decision:~:text=leave%20it%20empty.-,Authorize%20client%20with%20individual%20decision,-%7B%7BapiPath%7D%7D/governance%2Dengine)

Identity Cloud provides the following artifacts to enable the PingOne Authorize:

* [PingOne Worker service](https://backstage.forgerock.com/docs/idcloud/latest/am-reference/services-configuration.html#realm-pingone-worker-service)
* [PingOne Authorize node](https://github.com/ForgeRock/tntp-ping-authorize/blob/main/docs/pingoneauthorize/README.md)

You must set up the following before using the PingOne Authorize and PingAuthorize nodes.

PingOne Authorize Setup:
* [Create an authorize policy](https://docs.pingidentity.com/r/en-us/pingone/p1az_policies)
* [Create a worker application](https://docs.pingidentity.com/r/en-us/pingone/p1_add_app_worker)
    * Requires [Identity Data Admin](https://apidocs.pingidentity.com/pingone/platform/v1/api/#roles) role
* [PingOne Worker service](https://backstage.forgerock.com/docs/idcloud/latest/am-reference/services-configuration.html#realm-pingone-worker-service)


<!-- SUPPORT -->
## Support

If you encounter any issues, be sure to check our **[Troubleshooting](https://backstage.forgerock.com/knowledge/kb/article/a68547609)** pages.

Support tickets can be raised whenever you need our assistance; here are some examples of when it is appropriate to open a ticket (but not limited to):

* Suspected bugs or problems with Ping Identity software.
* Requests for assistance

You can raise a ticket using **[BackStage](https://backstage.forgerock.com/support/tickets)**, our customer support portal that provides one stop access to Ping Identity services.

BackStage shows all currently open support tickets and allows you to raise a new one by clicking **New Ticket**.

<!-- COLLABORATION -->

## Contributing

This Ping Identity project does not accept third-party code submissions.

<!------------------------------------------------------------------------------------------------------------------------------------>
<!-- LEGAL -->

## Disclaimer

> **This code is provided by Ping Identity on an “as is” basis, without warranty of any kind, to the fullest extent permitted by law.
>Ping Identity does not represent or warrant or make any guarantee regarding the use of this code or the accuracy,
>timeliness or completeness of any data or information relating to this code, and Ping Identity hereby disclaims all warranties whether express,
>or implied or statutory, including without limitation the implied warranties of merchantability, fitness for a particular purpose,
>and any warranty of non-infringement. Ping Identity shall not have any liability arising out of or related to any use,
>implementation or configuration of this code, including but not limited to use for any commercial purpose.
>Any action or suit relating to the use of the code may be brought only in the courts of a jurisdiction wherein
>Ping Identity resides or in which Ping Identity conducts its primary business, and under the laws of that jurisdiction excluding its conflict-of-law provisions.**

<!------------------------------------------------------------------------------------------------------------------------------------>
<!-- LICENSE - Links to the MIT LICENSE file in each repo. -->

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

---

&copy; Copyright 2024 Ping Identity. All Rights Reserved

[pingidentity-logo]: https://www.pingidentity.com/content/dam/picr/nav/Ping-Logo-2.svg "Ping Identity Logo"