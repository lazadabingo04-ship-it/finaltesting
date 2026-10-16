# Aiden Rice Wholesale and Retail - Vercel setup
1. Upload everything inside this folder (api, public, package.json, vercel.json) to a GitHub repository.
2. vercel.com > Add New > Project > import the repo > Deploy.
3. In the project: Storage tab > Create > Upstash for Redis (free plan) > connect to the project.
4. Settings > Environment Variables > add ADMIN_PASSWORD = your own strong password.
5. Deployments > Redeploy (so the new settings apply).
6. Open your site. Scroll to the footer > "Staff login" > enter the password to open the Back Office.
7. Settings > Domains to add your own domain.
