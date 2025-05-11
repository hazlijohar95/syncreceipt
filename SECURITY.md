# Security Policy

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | :white_check_mark: |

## Reporting a Vulnerability

We take security seriously at SyncReceipt. If you discover a security vulnerability, please follow these steps:

1. **DO NOT** open a public issue
2. Send a detailed report to [INSERT SECURITY EMAIL]
3. Include:
   - Description of the vulnerability
   - Steps to reproduce
   - Potential impact
   - Suggested fix (if any)

We will acknowledge receipt within 24 hours and aim to:
- Confirm the vulnerability within 72 hours
- Release a patch within 2 weeks
- Publicly disclose after the patch is released

## Security Best Practices

When using SyncReceipt:
1. Always use strong passwords
2. Enable two-factor authentication when available
3. Keep your dependencies updated
4. Review your access tokens regularly
5. Monitor your application logs

## Security Features

SyncReceipt implements several security measures:
- Row Level Security (RLS) in Supabase
- Secure file upload handling
- Input validation and sanitization
- Secure password handling
- Protected API endpoints