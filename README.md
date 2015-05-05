# `<z-time-*>`

time element which all encapsulated from [github/time-elements](https://github.com/github/time-elements)

- `<z-time-relative>`
- `<z-time-ago>`
- `<z-time-local>`

## Attribtues

- `datetime`

## Examples

```
<ul>
  <li><z-time-relative datetime="2014-04-01T16:30:00-08:00">
    April 1, 2014
  </z-time-relative></li>
  <li><z-time-ago datetime="2012-04-01T16:30:00-08:00">
    April 1, 2014
  </z-time-ago></li>
  <li><z-time-ago datetime="2012-04-01T16:30:00-08:00" format="micro">
    April 1, 2014
  </z-time-ago></li>
  <li><z-time-local datetime="2014-04-01T16:30:00-08:00"
      month="short"
      day="numeric"
      year="numeric"
      hour="numeric"
      minute="numeric">
    April 1, 2014 4:30PM PDT
  </z-time-local></li>
</ul>
```
