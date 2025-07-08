# Supabase

Supabase is the open source Firebase alternative. It provides all the backend services you need to build a product:

## Features

- **Database**: Every Supabase project comes with a full Postgres database
- **Authentication**: Add user sign ups and logins, securing your data with Row Level Security
- **Auto-generated APIs**: Instantly generate a RESTful API from your database schema
- **Real-time subscriptions**: Listen to database changes and build multiplayer experiences
- **Storage**: Store and serve large files, images, videos, and documents
- **Edge Functions**: Write custom logic that runs close to your users
- **AI & Vector embeddings**: Build AI-powered applications with vector search

## Getting Started

1. After installation, access Supabase Studio at `http://your-server:8000`
2. Login with your configured dashboard credentials
3. Create your first project and start building!

## Important Notes

- **Security**: Make sure to change the default JWT secret and passwords
- **Email**: Configure SMTP settings for user authentication emails
- **Database**: Your Postgres database will be accessible on port 5432
- **API**: RESTful API will be available at `http://your-server:8000/rest/v1/`

## Architecture

Supabase consists of several components:
- **Kong**: API Gateway
- **GoTrue**: Authentication service
- **PostgREST**: Auto-generated REST API
- **Realtime**: WebSocket connections for real-time features
- **Storage**: File storage service
- **Postgres**: Primary database
- **Studio**: Web dashboard for managing your project

For more information, visit [supabase.com](https://supabase.com)
