# API Routes

## Authentication
POST /api/auth/login
POST /api/auth/logout
GET /api/auth/me

## Contacts
GET /api/lists
POST /api/lists
GET /api/contacts/:id

## Templates
GET /api/templates
POST /api/templates

## Campaigns
GET /api/campaigns
POST /api/campaigns
POST /api/campaigns/:id/send

## Tracking
GET /track/open
GET /track/click

## Unsubscribe
GET /unsubscribe
POST /unsubscribe
