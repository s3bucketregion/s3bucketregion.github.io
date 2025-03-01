# AWS S3 Bucket Region Checker

A simple web tool that generates a bash command to check the AWS region of S3 buckets. The generated command uses curl to fetch the x-amz-bucket-region header, which works for both public and private buckets.

## Usage

1. Enter AWS S3 bucket names (one per line).
2. Click “Generate Command”.
3. Click “Copy” to copy the command.
4. Paste and run it in your terminal.

## Features

- Works for any valid S3 bucket (public or private).
- No AWS credentials required.
- One-click copy feature for quick execution.
- Clears terminal output before running the command.
