# Web infrastructure design

Whiteboard projects: designing web infrastructures for the website
`www.foobar.com`, from a single server up to a scaled, secured and monitored
architecture.

## Learning objectives

- Draw a diagram covering the web stack and explain what each component does
- Explain system redundancy
- Know the acronyms: LAMP, SPOF, QPS

## Requirements

- Everything is written in English
- Each task has a diagram (a picture of the whiteboard), uploaded to an image
  hosting service, and its link is written at the top of the answer file
- All files end with a new line
- This project is manually reviewed: each task is also whiteboarded in front
  of a mentor, staff or student, without a computer or notes

## Tasks

| # | File | Description |
|---|------|-------------|
| 0 | `0-simple_web_stack` | One server with Nginx, an application server, the code base and MySQL, reachable at `www.foobar.com` |
| 1 | `1-distributed_web_infrastructure` | Three servers: HAProxy load balancer and two servers, with a MySQL Primary-Replica cluster |
| 2 | `2-secured_and_monitored_web_infrastructure` | Adds 3 firewalls, an SSL certificate for HTTPS, and 3 monitoring clients |
| 3 | `3-scale_up` | Adds a clustered HAProxy load balancer and splits the web server, application server and database onto their own servers |

## Key terms

- **LAMP:** Linux, Apache, MySQL, PHP, a common web stack
- **SPOF:** Single Point Of Failure, a component whose failure stops the whole
  system
- **QPS:** Queries Per Second, the number of requests handled each second
