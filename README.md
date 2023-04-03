![Photo by Dimitri Iakymuk on Unsplash](https://user-images.githubusercontent.com/2342458/214546464-033f2a3d-189f-42a3-ad30-11d80358f6c1.png)

# Kinsta - Python Starter

An example of how to set **Python** up to enable deployment on Kinsta App Hosting services.

---
Kinsta is a developer-centric cloud host / PaaS. We’re striving to make it easier for you to share your web projects with your users. Focus on coding and building, and we’ll take care of deployment and provide fast, scalable hosting. + 24/7 expert-only support.

- [Start your free trial](https://kinsta.com/signup/?product_type=app-db)
- [Application Hosting](https://kinsta.com/application-hosting)
- [Database Hosting](https://kinsta.com/database-hosting)

## Dependency Management
**Kinsta** will automatically install dependencies defined in your `requirements.txt` file.

## Web Server Setup
### Start Command
When deploying an application Kinsta will automatically create a processes based on the `Procfile` in the root of the repository. Make sure to use this command to run your server:
```
web: python server.py
```
