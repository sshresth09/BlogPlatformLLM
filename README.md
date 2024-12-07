# aiblogplatform
## Setup
1. Run the development server:
```
npm run dev
or
yarn dev
or
pnpm dev
or 
bun dev
```

2. Create your .env file as follows:
```
NEXT_PUBLIC_SUPABASE_URL=""
NEXT_PUBLIC_SUPABASE_ANON_KEY=""
TAVILY_API_KEY=""
OPENAI_API_KEY=""
```

3. Create a project on [Supabase](http://supabase.com/) to get your Supabase URL and API KEY.
4. Get your Tavily api key from [Tavily](https://app.tavily.com/home).

## Deployment

### 1. Create a Vercel Account
   
    Go to Vercel's website.
    
    Sign up or log in using GitHub, GitLab, or Bitbucket.

### 2. Connect Your Repository to Vercel
   
    Click "New Project" in your Vercel dashboard.
    
    Select the Git repository where your Next.js project is hosted (GitHub, GitLab, or Bitbucket).
    
    Authorize Vercel to access your repository.

### 3. Configure Your Project Settings
   
    Vercel will detect that the project is a Next.js application automatically.
    
    Confirm the settings:
    
    Framework Preset: Next.js
    
    Root Directory: "./"
    
    Add Environment Variables:
    
    NEXT_PUBLIC_SUPABASE_URL=""
    NEXT_PUBLIC_SUPABASE_ANON_KEY=""
    TAVILY_API_KEY=""
    OPENAI_API_KEY=""
  
### 4. Deploy the Project
   
    Click "Deploy" to start the deployment process.
    
    Vercel will build and deploy your project. This may take a few minutes.

### 5. Verify Deployment
    
    Once the deployment is complete, you’ll receive a unique URL for your live project, e.g., https://your-project.vercel.app.
    
    Test the URL to ensure everything works as expected.

### 6. Manage Your Deployment
    
    Use the Vercel dashboard to manage deployments and track performance.
    
    Any updates pushed to the connected Git repository will trigger an automatic redeployment.

