# Django Custom Authentication Project

## Overview

This Django project implements a custom authentication system that uses both email and phone number for user authentication. Users can sign up and log in using either their email or phone number, and both will be verified before the account becomes active.

### Features

- **Custom User Model**: Replaces the default Django `User` model to use email and phone number as the primary credentials.
- **Email Verification**: Users must verify their email via a confirmation link sent during registration.
- **Phone Number Verification**: Users are required to verify their phone number with an OTP (One-Time Password) sent via SMS.
- **Login Options**: Users can log in using either their email or phone number.
- **Password Reset**: Password reset functionality using both email and phone number.

## Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/KevinAnce/django_use_custom_auth.git
cd django_use_custom_auth
