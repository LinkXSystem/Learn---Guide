# Github's Hook 的数据格式

## Issue 的 Comment 的格式

```json
{
  "action": "created",
  "issue": {
    "url": "https://api.github.com/repos/LinkXSystem/learn-guide/issues/7",
    "repository_url": "https://api.github.com/repos/LinkXSystem/learn-guide",
    "labels_url": "https://api.github.com/repos/LinkXSystem/learn-guide/issues/7/labels{/name}",
    "comments_url": "https://api.github.com/repos/LinkXSystem/learn-guide/issues/7/comments",
    "events_url": "https://api.github.com/repos/LinkXSystem/learn-guide/issues/7/events",
    "html_url": "https://github.com/LinkXSystem/learn-guide/issues/7",
    "id": 509701377,
    "node_id": "MDU6SXNzdWU1MDk3MDEzNzc=",
    "number": 7,
    "title": "测试 robot 的 issue :construction:",
    "user": {
      "login": "LinkXSystem",
      "id": 26039188,
      "node_id": "MDQ6VXNlcjI2MDM5MTg4",
      "avatar_url": "https://avatars2.githubusercontent.com/u/26039188?v=4",
      "gravatar_id": "",
      "url": "https://api.github.com/users/LinkXSystem",
      "html_url": "https://github.com/LinkXSystem",
      "followers_url": "https://api.github.com/users/LinkXSystem/followers",
      "following_url": "https://api.github.com/users/LinkXSystem/following{/other_user}",
      "gists_url": "https://api.github.com/users/LinkXSystem/gists{/gist_id}",
      "starred_url": "https://api.github.com/users/LinkXSystem/starred{/owner}{/repo}",
      "subscriptions_url": "https://api.github.com/users/LinkXSystem/subscriptions",
      "organizations_url": "https://api.github.com/users/LinkXSystem/orgs",
      "repos_url": "https://api.github.com/users/LinkXSystem/repos",
      "events_url": "https://api.github.com/users/LinkXSystem/events{/privacy}",
      "received_events_url": "https://api.github.com/users/LinkXSystem/received_events",
      "type": "User",
      "site_admin": false
    },
    "labels": [],
    "state": "open",
    "locked": false,
    "assignee": null,
    "assignees": [],
    "milestone": null,
    "comments": 1,
    "created_at": "2019-10-21T02:47:10Z",
    "updated_at": "2020-01-04T02:35:37Z",
    "closed_at": null,
    "author_association": "OWNER",
    "body": "用于测试功能 ，谨慎使用"
  },
  "comment": {
    "url": "https://api.github.com/repos/LinkXSystem/learn-guide/issues/comments/570749593",
    "html_url": "https://github.com/LinkXSystem/learn-guide/issues/7#issuecomment-570749593",
    "issue_url": "https://api.github.com/repos/LinkXSystem/learn-guide/issues/7",
    "id": 570749593,
    "node_id": "MDEyOklzc3VlQ29tbWVudDU3MDc0OTU5Mw==",
    "user": {
      "login": "LinkXSystem",
      "id": 26039188,
      "node_id": "MDQ6VXNlcjI2MDM5MTg4",
      "avatar_url": "https://avatars2.githubusercontent.com/u/26039188?v=4",
      "gravatar_id": "",
      "url": "https://api.github.com/users/LinkXSystem",
      "html_url": "https://github.com/LinkXSystem",
      "followers_url": "https://api.github.com/users/LinkXSystem/followers",
      "following_url": "https://api.github.com/users/LinkXSystem/following{/other_user}",
      "gists_url": "https://api.github.com/users/LinkXSystem/gists{/gist_id}",
      "starred_url": "https://api.github.com/users/LinkXSystem/starred{/owner}{/repo}",
      "subscriptions_url": "https://api.github.com/users/LinkXSystem/subscriptions",
      "organizations_url": "https://api.github.com/users/LinkXSystem/orgs",
      "repos_url": "https://api.github.com/users/LinkXSystem/repos",
      "events_url": "https://api.github.com/users/LinkXSystem/events{/privacy}",
      "received_events_url": "https://api.github.com/users/LinkXSystem/received_events",
      "type": "User",
      "site_admin": false
    },
    "created_at": "2020-01-04T02:35:37Z",
    "updated_at": "2020-01-04T02:35:37Z",
    "author_association": "OWNER",
    "body": "数据测试"
  },
  "repository": {
    "id": 104758952,
    "node_id": "MDEwOlJlcG9zaXRvcnkxMDQ3NTg5NTI=",
    "name": "learn-guide",
    "full_name": "LinkXSystem/learn-guide",
    "private": false,
    "owner": {
      "login": "LinkXSystem",
      "id": 26039188,
      "node_id": "MDQ6VXNlcjI2MDM5MTg4",
      "avatar_url": "https://avatars2.githubusercontent.com/u/26039188?v=4",
      "gravatar_id": "",
      "url": "https://api.github.com/users/LinkXSystem",
      "html_url": "https://github.com/LinkXSystem",
      "followers_url": "https://api.github.com/users/LinkXSystem/followers",
      "following_url": "https://api.github.com/users/LinkXSystem/following{/other_user}",
      "gists_url": "https://api.github.com/users/LinkXSystem/gists{/gist_id}",
      "starred_url": "https://api.github.com/users/LinkXSystem/starred{/owner}{/repo}",
      "subscriptions_url": "https://api.github.com/users/LinkXSystem/subscriptions",
      "organizations_url": "https://api.github.com/users/LinkXSystem/orgs",
      "repos_url": "https://api.github.com/users/LinkXSystem/repos",
      "events_url": "https://api.github.com/users/LinkXSystem/events{/privacy}",
      "received_events_url": "https://api.github.com/users/LinkXSystem/received_events",
      "type": "User",
      "site_admin": false
    },
    "html_url": "https://github.com/LinkXSystem/learn-guide",
    "description": "有趣的学习笔记 (*^_^*)",
    "fork": false,
    "url": "https://api.github.com/repos/LinkXSystem/learn-guide",
    "forks_url": "https://api.github.com/repos/LinkXSystem/learn-guide/forks",
    "keys_url": "https://api.github.com/repos/LinkXSystem/learn-guide/keys{/key_id}",
    "collaborators_url": "https://api.github.com/repos/LinkXSystem/learn-guide/collaborators{/collaborator}",
    "teams_url": "https://api.github.com/repos/LinkXSystem/learn-guide/teams",
    "hooks_url": "https://api.github.com/repos/LinkXSystem/learn-guide/hooks",
    "issue_events_url": "https://api.github.com/repos/LinkXSystem/learn-guide/issues/events{/number}",
    "events_url": "https://api.github.com/repos/LinkXSystem/learn-guide/events",
    "assignees_url": "https://api.github.com/repos/LinkXSystem/learn-guide/assignees{/user}",
    "branches_url": "https://api.github.com/repos/LinkXSystem/learn-guide/branches{/branch}",
    "tags_url": "https://api.github.com/repos/LinkXSystem/learn-guide/tags",
    "blobs_url": "https://api.github.com/repos/LinkXSystem/learn-guide/git/blobs{/sha}",
    "git_tags_url": "https://api.github.com/repos/LinkXSystem/learn-guide/git/tags{/sha}",
    "git_refs_url": "https://api.github.com/repos/LinkXSystem/learn-guide/git/refs{/sha}",
    "trees_url": "https://api.github.com/repos/LinkXSystem/learn-guide/git/trees{/sha}",
    "statuses_url": "https://api.github.com/repos/LinkXSystem/learn-guide/statuses/{sha}",
    "languages_url": "https://api.github.com/repos/LinkXSystem/learn-guide/languages",
    "stargazers_url": "https://api.github.com/repos/LinkXSystem/learn-guide/stargazers",
    "contributors_url": "https://api.github.com/repos/LinkXSystem/learn-guide/contributors",
    "subscribers_url": "https://api.github.com/repos/LinkXSystem/learn-guide/subscribers",
    "subscription_url": "https://api.github.com/repos/LinkXSystem/learn-guide/subscription",
    "commits_url": "https://api.github.com/repos/LinkXSystem/learn-guide/commits{/sha}",
    "git_commits_url": "https://api.github.com/repos/LinkXSystem/learn-guide/git/commits{/sha}",
    "comments_url": "https://api.github.com/repos/LinkXSystem/learn-guide/comments{/number}",
    "issue_comment_url": "https://api.github.com/repos/LinkXSystem/learn-guide/issues/comments{/number}",
    "contents_url": "https://api.github.com/repos/LinkXSystem/learn-guide/contents/{+path}",
    "compare_url": "https://api.github.com/repos/LinkXSystem/learn-guide/compare/{base}...{head}",
    "merges_url": "https://api.github.com/repos/LinkXSystem/learn-guide/merges",
    "archive_url": "https://api.github.com/repos/LinkXSystem/learn-guide/{archive_format}{/ref}",
    "downloads_url": "https://api.github.com/repos/LinkXSystem/learn-guide/downloads",
    "issues_url": "https://api.github.com/repos/LinkXSystem/learn-guide/issues{/number}",
    "pulls_url": "https://api.github.com/repos/LinkXSystem/learn-guide/pulls{/number}",
    "milestones_url": "https://api.github.com/repos/LinkXSystem/learn-guide/milestones{/number}",
    "notifications_url": "https://api.github.com/repos/LinkXSystem/learn-guide/notifications{?since,all,participating}",
    "labels_url": "https://api.github.com/repos/LinkXSystem/learn-guide/labels{/name}",
    "releases_url": "https://api.github.com/repos/LinkXSystem/learn-guide/releases{/id}",
    "deployments_url": "https://api.github.com/repos/LinkXSystem/learn-guide/deployments",
    "created_at": "2017-09-25T14:15:13Z",
    "updated_at": "2020-01-03T11:47:29Z",
    "pushed_at": "2020-01-03T11:47:26Z",
    "git_url": "git://github.com/LinkXSystem/learn-guide.git",
    "ssh_url": "git@github.com:LinkXSystem/learn-guide.git",
    "clone_url": "https://github.com/LinkXSystem/learn-guide.git",
    "svn_url": "https://github.com/LinkXSystem/learn-guide",
    "homepage": "https://linkxsystem.github.io/",
    "size": 49435,
    "stargazers_count": 1,
    "watchers_count": 1,
    "language": "JavaScript",
    "has_issues": true,
    "has_projects": true,
    "has_downloads": true,
    "has_wiki": true,
    "has_pages": false,
    "forks_count": 1,
    "mirror_url": null,
    "archived": false,
    "disabled": false,
    "open_issues_count": 18,
    "license": null,
    "forks": 1,
    "open_issues": 18,
    "watchers": 1,
    "default_branch": "master"
  },
  "sender": {
    "login": "LinkXSystem",
    "id": 26039188,
    "node_id": "MDQ6VXNlcjI2MDM5MTg4",
    "avatar_url": "https://avatars2.githubusercontent.com/u/26039188?v=4",
    "gravatar_id": "",
    "url": "https://api.github.com/users/LinkXSystem",
    "html_url": "https://github.com/LinkXSystem",
    "followers_url": "https://api.github.com/users/LinkXSystem/followers",
    "following_url": "https://api.github.com/users/LinkXSystem/following{/other_user}",
    "gists_url": "https://api.github.com/users/LinkXSystem/gists{/gist_id}",
    "starred_url": "https://api.github.com/users/LinkXSystem/starred{/owner}{/repo}",
    "subscriptions_url": "https://api.github.com/users/LinkXSystem/subscriptions",
    "organizations_url": "https://api.github.com/users/LinkXSystem/orgs",
    "repos_url": "https://api.github.com/users/LinkXSystem/repos",
    "events_url": "https://api.github.com/users/LinkXSystem/events{/privacy}",
    "received_events_url": "https://api.github.com/users/LinkXSystem/received_events",
    "type": "User",
    "site_admin": false
  }
}
```