# Codespaces-
Configurations between codespaces and github// Octokit.js // https://github.com/octokit/core.js#readme const octokit = new Octokit({   auth: 'YOUR-TOKEN' })  await octokit.request('GET /repos/{owner}/{repo}/codespaces/devcontainers', {   owner: 'OWNER',   repo: 'REPO',   headers: {     'X-GitHub-Api-Version': '2022-11-28'   } })
