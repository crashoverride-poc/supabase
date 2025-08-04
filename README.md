# Supabase Fork with Chalk Integration

This is a fork of [Supabase](https://github.com/supabase/supabase) with CI/CD workflows to build chalked Docker images.

## Workflows

- **sync-upstream.yml** - Syncs upstream Supabase source code to the `upstream` branch every 30 minutes
- **chalk-and-push.yml** - Builds and pushes Docker images with Chalk instrumentation to AWS ECR
- **weekly-prod-build.yml** - Retags dev images as prod weekly

## Images Built

- **studio** - Supabase Studio dashboard