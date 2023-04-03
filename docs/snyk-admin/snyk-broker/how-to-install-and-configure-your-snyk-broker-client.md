# Upgrade the Snyk Broker Client

Snyk regularly updates the Broker Client in order to provide new features, bug fixes, and more. The full list of versions with release notes is available on [Snyk Broker GitHub](https://github.com/snyk/broker/releases). Snyk encourages you to [subscribe to the RSS feed](https://github.com/snyk/broker/releases.atom) for that page to receive information about versions as they are released.

When you upgrade your Broker there may be some new rules added that Snyk requires to function correctly. Therefore, you will need to re-initialize your API allow-list. If you added or removed any rules to [customize your allow-list](https://docs.snyk.io/snyk-admin/snyk-broker/how-to-install-and-configure-your-snyk-broker-client/advanced-configuration-for-snyk-broker-docker-installation#custom-approved-listing-filter) (for example, to support files greater in size than 1Mb), you must re-apply these changes to the new allow-list.