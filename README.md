This playbook is a good starting point for understanding how to get a basic consul cluster up and running in an on-prem VM environment. **This is currently not a production worthy effort, you would be seriously negligant to use it for prod purposes.**



At this point in time there are a bunch of hard coded constants in this playbook, To get it working, spin up some VM's and update the `inventory` and `templates/config.json` with the appropriate values.

There is abundant information online at the [official consul docs](https://www.consul.io/docs/agent/options.html)

