K95002127: Troubleshooting BIG-IP failover events
https://support.f5.com/csp/article/K95002127

https://techdocs.f5.com/kb/en-us/products/big-ip_ltm/manuals/product/bigip-system-device-service-clustering-administration-13-0-0.html

```bash
tmsh show /cm failover-status
tmsh run /cm watch-sys-device
