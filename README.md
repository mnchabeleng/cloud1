# Cloud 1

## Objective
Deploy / Install a simple wordpress website on a cloud infrastructure

- Your website must be running at all times on at least 2 servers, if possible located in different server farms.
- Some sort of mecanism will randomly and evenly redirect visitors to any of your servers.
- Traffic pikes will trigger the launch of other servers with perfectly synced data (and the other way around if the traffic fades).
- Logged in users will stay identified for the length of a normal session, no matter what.
- Static content should be distributed as best as you can (CDN).
- New content on the site should be available across all instances immediately (or at least within a few seconds).
- Any failure should be handled so that your website is always available.
- Hosting cost should reflect your actual usage.
- The public should not even be able to reach anything they have no reason to reach.

![Screenshot](https://raw.githubusercontent.com/mnchabeleng/cloud1/master/screenshots/wordpress-arch-v2.f065678e8a2d45a770dc192747d49f939ccd5ac9.png)

## Choice of platform
AWS

## Load Balancer URL
http://cloud1-load-balancer-725219300.us-east-2.elb.amazonaws.com/