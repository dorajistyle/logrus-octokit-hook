logrus-octokit-hook
==========

Package logrus-octokit-hook provides a Github hook using the [octokit] for the [logrus] loggin package.

## Mehtod

```Go
NewOctokitHook(gitHubAPIURL string,
		userAgent string,
		accessToken string,
		owner string,
		repo string))
```

## Example

```Go
logrus.AddHook(octokit.NewOctokitHook("https://api.github.com"
		"Goyangi(using Octokit Go) 1.0",
		"012323abcdabcdgithubtoken",
		"dorajistyle",
		"goyangi"))

```

[logrus]: https://github.com/sirupsen/logrus
[octokit]: https://github.com/octokit/go-octokit
---

logrus-octokit-hook is under the [MIT license](./LICENSE)
