# S-NAS
The aim of this project is to easily deploy a secured NAS for your home. It just contains the following containers: Nextcloud, Bitwaurden, MySQL, PHPMyAdmin, Tailscale and Traefik. 


# Security Design

This proyect is aligned with the S-SDLC. The steps I followed to achieve a secure posture are the following:

1. Identify the software that we want to
2. Understand the versions that will be needed that don't have a critical security issue.
3. Work with SAST tools to analyze the content of the images of Docker containers that will be running.
4. Work with DAST tools to analyze any vulnerability during the running Docker containers.
5. Work with IAST tools to combine the SAST & DAST features.
