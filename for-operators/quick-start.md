# Operators Quick Start

_**This guide is in-progress.**_

This guide is for people who want to operate their own Mastodon instance. This is an opinionated guide that outlines one method of setting up a Mastodon instance, but there are a variety of other ways to do so. Your millage may vary.

## Basic Concepts

To operate your own Mastodon instance, you'll need the following:

* A server to run your Mastodon instance on. This server will run the Mastodon application code and the required database and cache systems.
* A domain name.

## Domains and DNS

What I did: Registered through dnsimple.com

## Server and Hosting

What I did: Using a 2g linode server running Debian 8. Installed nginx, docker, and letsencrypt via apt.

## Email

What I did: Signed up with mailgun.

## Mastodon Application

What I did: Cloned the git repository, built the application, ran the application containers using docker compose.

## Proxy

What I did: Configured nginx to proxy to the local Mastodon containers.

## Closing

Up-front cost was $14 for the domain.

On-going cost will vary: $20 a month for the linode host, unknown for mailgun.



