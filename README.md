# Author

Created by Qian Shao

# FreeCodeCamp API Projects: Timestamp Microservice
### 用户故事：
1. 把一个字符串作为参数，判断该字符串是不是一个 Unix 时间，或者一个公历日期（例如：January 1, 2016）。
2. 如果是，那么它同时返回 Unix 时间戳和公历日期。
3. 如果不是，那么它返回 null 。

## Example usage:

```url
https://timestamp-ms.herokuapp.com/December%2015,%202015
https://timestamp-ms.herokuapp.com/1450137600
```

## Example output:

```json
{ "unix": 1450137600, "natural": "December 15, 2015" }
```
