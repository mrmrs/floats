# FLOATS

  Mobile-first float classes.
  Set the desired float on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

```
.fl { float: left;  display: inline; }
.fr { float: right; display: inline; }
.fn { float: none; }

@media screen and (min-width: 48em) {
  .fl-ns { float: left;  display: inline; }
  .fr-ns { float: right; display: inline; }
  .fn-ns { float: none; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .fl-m { float: left;  display: inline; }
  .fr-m { float: right; display: inline; }
  .fn-m { float: none; }
}

@media screen and (min-width: 64em)  {
  .fl-l { float: left;  display: inline; }
  .fr-l { float: right; display: inline; }
  .fn-l { float: none; }
}
```
