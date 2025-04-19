# Supabase Stacks

This folder contains various stacks for Supabase. Most of them are AI enablement stacks but also a few stacks for content enablement and fullstack projects. See corresponding instructions and `docker-compose.yml` files for each stack in its respective directory.

The `docker` folder is used to run the Supabase Docker image locally. To run the Docker image, navigate to the `docker` folder and run the following command:

```bash
docker-compose up
```

This will start the Supabase Docker image locally. For more information on how to use the Supabase Docker image, see the [Supabase Docker documentation](https://supabase.com/docs/guides/docker).

The other folders build on top of the Supabase Docker image and provide additional functionality. Each folder contains its own `docker-compose.yml` file and instructions for running the stack locally.
