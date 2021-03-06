## youtous/ansible-logwatch [![Build Status](https://travis-ci.org/youtous/ansible-logwatch.png)](https://travis-ci.org/youtous/ansible-logwatch)

Ansible role which installs and configures logwatch.

Forked from ANXS.logwatch in order to maintain the role updated.

#### Requirements & Dependencies

- Tested on Ansible 2.9.6 or higher.
- No dependencies


#### Variables

```yaml
logwatch_email: "root@localhost"  # Email Address which Logwatch reports to
logwatch_detail: "low"            # The level of detail in the Logwatch report
logwatch_range: "yesterday"       # The default time range for the Logwatch report
logwatch_output: "stdout"         # The output method of the Logwatch report
logwatch_format: "text"           # The format of the Logwatch report
logwatch_cron_time: "daily"       # Cron special time specification nickname - must match with logwatch range!
```


#### Testing
This project comes with a VagrantFile, this is a fast and easy way to test changes to the role, fire it up with `vagrant up`

See [vagrant docs](https://docs.vagrantup.com/v2/) for getting setup with vagrant


#### License

Licensed under the MIT License. See the LICENSE file for details.


#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/youtous/ansible-logwatch/issues)!
