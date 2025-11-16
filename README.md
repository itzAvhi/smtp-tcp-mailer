# smtp-tcp-mailer
SMTP TCP Mailer (Go)

A simple and minimal email sender built in Go using SMTP over TCP.
This project shows how to build a raw SMTP message, authenticate, and send it to a mail server (like Gmail) using Go’s built-in net/smtp package.

Features

Plain-text email sending

SMTP authentication

Works with Gmail (App Password required)

Clean and easy-to-read code

Usage

Update the config in main.go with your:

SMTP host

Port

Sender email

App password

Recipient address

Then run:

go run main.go

Purpose

Made for learning how SMTP works at a basic TCP level in Go.
