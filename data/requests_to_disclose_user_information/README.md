# Requests to disclose user information

GitHub’s [Guidelines for Legal Requests of User Data](https://help.github.com/articles/guidelines-for-legal-requests-of-user-data/) explain how we handle legally authorized requests, including law enforcement requests, subpoenas, court orders, and search warrants, as well as national security letters and orders.

We follow the law while requiring adherence to the highest legal standards for user requests for data. Some kinds of legally authorized requests for user data, typically limited in scope, do not require review by a judge or a magistrate. For example, both subpoenas and national security letters are written orders to compel someone to produce documents or testify on a particular subject, and neither requires judicial review. National security letters are further limited in that they can only be used for matters of national security.

By contrast, search warrants and court orders both require judicial review. A national security order is a type of court order that can be put in place, for example, to produce information or authorize surveillance. National security orders are issued by the [Foreign Intelligence Surveillance Court](https://epic.org/privacy/surveillance/fisa/fisc/), a specialized US court for national security matters.

As we note in our [guidelines](https://help.github.com/articles/guidelines-for-legal-requests-of-user-data/):

- We only release information to third parties when the appropriate legal requirements have been satisfied, or where we believe it’s necessary to comply with our legal requirements, or to prevent an emergency involving danger of death or serious physical injury to a person.
- We require a subpoena to disclose certain kinds of user information, like a name, an email address, or an IP address associated with an account, unless under rare, exigent circumstances. Exigent circumstances refers to cases where we determine that disclosure is necessary to prevent an emergency involving danger of death or serious physical injury to a person, and we keep disclosure as limited as possible in relation to the emergency.
- We require a court order or search warrant for all other kinds of user information, like user access logs and account settings. We require a search warrant for private account contents, such as the contents of a private repository.
- We notify all affected users about any requests for their account information, except where we are prohibited from doing so by law or court order.

## Disclosure and notification

We carefully review all requests to disclose user data to ensure they adhere to our policies and satisfy all appropriate legal requirements, and we push back where they do not. As a result, we didn’t disclose user information in response to every request we received. In some cases, the request was not specific enough, and the requesting party withdrew the request after we asked for clarification. In other cases, we received very broad requests, and we were able to limit the scope of the information we provided.

When we do disclose information, we never share private content data, except in response to a search warrant. Content data includes, for example, content hosted in private repositories. With all other requests, we only share non-content data, which includes basic account information, such as username and email address, metadata (such as information about account usage or permissions), and log data regarding account activity or access history.

We notify users when we disclose their information in response to a legal request, unless a law or court order prevents us from doing so. In many cases, legal requests are accompanied by a court order that prevents us from notifying users, commonly referred to as a gag order.

## National security letters and orders

We’re very limited in what we can legally disclose about [national security letters](https://epic.org/privacy/nsl/) and [Foreign Intelligence Surveillance Act (FISA) orders](https://epic.org/privacy/surveillance/fisa/fisc/). We report information about these types of requests in ranges of 250, starting with zero.

## Cross-border data requests

Governments outside the US can make cross-border data requests for user information through the DOJ via a mutual legal assistance treaty (MLAT) or similar form of international legal process. Our [Guidelines for Legal Requests of User Data](https://help.github.com/en/github/site-policy/guidelines-for-legal-requests-of-user-data#requests-from-foreign-law-enforcement) explain how we handle user information requests from foreign law enforcement. Essentially, when a foreign government seeks user information from GitHub, we direct the government to the DOJ so that the DOJ can determine whether the request complies with US legal protections.

If it does, the DOJ would send us a subpoena, court order, or search warrant, which we would then process like any other requests we receive from the US government. When we receive these requests from the DOJ, they don’t necessarily come with enough context for us to know whether they’re originating from another country. However, when a request does indicate this, we capture that information in our statistics for subpoenas, court orders, and search warrants.
