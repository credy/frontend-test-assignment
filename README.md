# Credy

## Frotned developer position's test task

------------------------------------------------------------------------------------------------------------------------

### Task: Write an application in VueJS called “Group Blog”.

**Description**

There are people who can post text posts into the blog. Also there should be user-friendly interface to manage the posts. Anonymous users should have possibility to read posts while registered users can create new posts and edit their own ones. The blog API is at https://frontend.recruiting.credy.com/

------------------------------------------------------------------------------------------------------------------------

### API Documentation
API supports application/json, text/html based on accept and content-type headers

#### Valid routes
| Method | Route      | Description                    |
|:----|:-----------|:----------------------------------|
| GET | `/posts` | Returns a list of posts |
| POST | `/posts` | Creates new post |
| GET | `/posts/{ID}` | Returns specific post |
| PUT | `/posts/{ID}` | Updates specific post |
| DELETE | `/posts/{ID}` | Deletes specific post |
| GET | `/auth` | API login route using OAuth2. client_secret="secret", client_id="client" |

#### Accepted headers
| Header | Description
|:-------|:-----------|
| accept | In witch format client expects data |
| content-type | In witch format client sends data |
| x-pagination-current-page | Current page |
| x-pagination-page-count | Total count of pages |
| x-pagination-per-page | Resources per page |
| x-pagination-total-count | Total count of resources |

## Scoring & review

Please use github.com or gitlab.com to publish your application. When its finished, drop us a link. It will be reviewed by our developers and you will be given feedback taking into account the table below. 

You should be proud of your own code.

| Max points | Topic | Entry level | Middle level | Senior developer |
|:----------:|---------------------------------------------------------------------------------------------------|-------------|--------------|------------------|
| 1 | Git usage <br><ul><li>explanatory commit messages</li><li>reasonable amount of functionality in a commit</li></ul> | X | X | X |
| 1 | User interface <br><ul><li>Mobile friendly</li><li>Decent looking</li></ul> | X | X | X |
| 3 | Internationalization support <br><ul><li>handling plural forms</li> <li>no concatenations</li><li>proper number formatting</li></ul> |  | X | X |
| 2 | Documentation <br><ul><li>easy to follow documentation</li><li>MarkDown</li></ul> |  | X | X |
| 1 | NodeJS compatibility from 6.10+ |  | X | X |
| 1 | Proper error handling |  |  | X |
| 2 | Usage of VueX store <br><ul><li>State in general store</li><li>State should stay after page refresh</li></ul> |  | X | X |
| 1 | Optimal memory usage |  |  | X |
| 1 | Caching & cache invalidation [clicky :)](https://martinfowler.com/bliki/TwoHardThings.html)  |  |  | X |
| 2 | Automated tests <br><ul><li>unit</li><li>functional</li><li>Auto run tests in gitlab / github at each push</li></ul> |  |  | X |