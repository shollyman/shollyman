```sql
  SELECT
    product, lang, repo, issues
  FROM
    [google.cloud](https://cloud.google.com/).developer_relations
  WHERE
    user_id = 'shollyman'
    AND role IN ('library_maintainer','engineer','blowhard')
    AND activity_frequency IN ('all_too_much','often')
```

Results:

| product  | lang   | repo                                                  | issues                                                                                                                    |
|----------|--------|-------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------|
| BigQuery | ALL    |                                                       | [public issue tracker](https://issuetracker.google.com/savedsearches/559654?pli=1)                                        |
| BigQuery | go     | https://github.com/googleapis/google-cloud-go         | [repo](https://github.com/googleapis/google-cloud-go/issues?q=is%3Aissue+is%3Aopen+label%3A%22api%3A+bigquery%22)         |
| BigQuery | go     | https://github.com/GoogleCloudPlatform/golang-samples | [repo](https://github.com/GoogleCloudPlatform/golang-samples/issues?q=is%3Aissue+is%3Aopen+label%3A%22api%3A+bigquery%22) |
| BigQuery | python | https://github.com/googleapis/python-bigquery         | [repo](https://github.com/googleapis/python-bigquery/issues?q=is%3Aissue+is%3Aopen+label%3A%22api%3A+bigquery%22)         |
| BigQuery | java   | https://github.com/googleapis/java-bigquery           | [repo](https://github.com/googleapis/java-bigquery/issues?q=is%3Aissue+is%3Aopen+label%3A%22api%3A+bigquery%22)           |



