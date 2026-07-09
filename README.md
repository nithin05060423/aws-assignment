# AWS DevOps Engineer Intern Assignment

## Objective
Deploy a simple website on an AWS EC2 Ubuntu instance using Nginx.

## AWS Services Used
- Amazon EC2
- Security Groups

## Linux Commands Used

```bash
sudo apt update
sudo apt install nginx -y
sudo systemctl status nginx
sudo systemctl restart nginx
df -h
free -h
ps aux
```

## Website Details
- Name: Nithin Goli
- College: Narasaraopet Engineering College
- Branch: Computer Science and Engineering
- Email: nithin934767@gmail.com

## Steps Performed
1. Created an Ubuntu EC2 instance.
2. Configured Security Group (Ports 22 and 80).
3. Connected using SSH.
4. Installed and configured Nginx.
5. Hosted a static HTML website.
6. Verified the website using the EC2 Public IP.

## Learnings
- AWS EC2
- Linux

- ## Bonus Task

### Created Another Security Group

As part of the bonus task, I created an additional AWS Security Group named **bonus-security-group**.

**Configuration:**
- SSH (Port 22)
- HTTP (Port 80)

This demonstrates the ability to create and configure AWS Security Groups for secure EC2 access.
- Nginx
- Git & GitHub
