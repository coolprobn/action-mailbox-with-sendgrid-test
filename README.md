# README

This is an example app for my blog article where I teach you how to setup Action Mailbox with SendGrid. You can find the blog at [Setup Action Mailbox with SendGrid](https://prabinpoudel.com.np/articles/action-mailbox-with-sendgrid)

## Dependency Versions

- Ruby: 3.0.0
- Rails and Action Mailbox: 7.0.2.4

## Setup

1. Clone the repo
2. Change the branch: `git checkout features/setup-sendgrid-in-local`
3. From the project root folder, install all required gems with `bundle install`
4. Fire the rails server: `rails s`
5. You can test inbound emails from the URL [Action Mailbox Inbound Email in Localhost](http://localhost:3000/rails/conductor/action_mailbox/inbound_emails/new)
6. You can test with NGROK in local by following the instructions in the blog at [Setup NGROK](https://prabinpoudel.com.np/articles/action-mailbox-with-sendgrid/#step-7-setup-ngrok)
