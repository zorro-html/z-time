# time

时间

* 封装自 https://github.com/github/time-elements

## Example

```
on 2 Apr
<jie-time-relative datetime="2014-04-01T16:30:00-08:00">
  April 1, 2014
</jie-time-relative>

3 years ago
<jie-time-ago datetime="2012-04-01T16:30:00-08:00">
  April 1, 2014
</jie-time-ago>

3y
<jie-time-ago datetime="2012-04-01T16:30:00-08:00" format="micro">
  April 1, 2014
</jie-time-ago>

2 Apr 2014 上午8:30
<jie-time-local datetime="2014-04-01T16:30:00-08:00"
    month="short"
    day="numeric"
    year="numeric"
    hour="numeric"
    minute="numeric">
  April 1, 2014 4:30PM PDT
</jie-time-local>
```
