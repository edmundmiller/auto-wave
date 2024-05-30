> [!WARNING]
> This project has been deprecated as it was a proof of concept. Use Seqera Containers https://seqera.io/containers/ instead.

# Auto-wave

Build ad-hoc containers with bioinformatics software.

We'll add freezing and pushing to a container registry soon™️!

## From a file

0. Create a directory
1. Create an `environment.yml` or `Dockerfile` file in that directory
2. Commit, push and open a PR to repo
3. Dig through the CI logs and find your container!

## Ad-hoc

1. Go to the [Manual Container Build](https://github.com/Emiller88/auto-wave/actions/workflows/user-input.yml) page.
2. Click on the `Run workflow` drop-down button.
3. Enter a string of conda packages to install.

Some valid examples:

- `bioconda::bowtie=1.3.0 bioconda::samtools=1.16.1`
- `bowtie=1.3.0 samtools`

Versions and channels are optional. Optional dependencies are up to you!

4. Dig through the CI logs and find your container!
