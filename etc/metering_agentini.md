## metering_agent.ini
metering agent 的配置信息，包括 metering 的频率、driver 等。

```
[DEFAULT]
# Show debugging output in log (sets DEBUG log level output)
# debug = True

# Default driver:
# driver = neutron.services.metering.drivers.noop.noop_driver.NoopMeteringDriver
# Example of non-default driver
# driver = neutron.services.metering.drivers.iptables.iptables_driver.IptablesMeteringDriver

# Interval between two metering measures
# measure_interval = 30

# Interval between two metering reports
# report_interval = 300

# interface_driver = neutron.agent.linux.interface.OVSInterfaceDriver

# use_namespaces = True

```
