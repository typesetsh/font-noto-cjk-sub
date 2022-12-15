# font-noto-cjk-sub
Noto CJK Substitute package for smaller package size.

If the CJK font files take up too much space for your deployment, and you don't require them
you can use this package to remove them.

### Install

Make sure you use a typeset.sh version `>= 0.23`.
Then install thise package, it will replace the CJK package.

```shell
composer require typesetsh/font-noto-cjk-sub
```

---

#### Optional
If you still want to support the CJK font set, you can do so by placing the fonts (_NotoSansCJKsc-*.otf_)
files somewhere on your project and add the path to the FontSelector using php.


```php
FontSelector::$fontDirs[] = '/var/fonts/NotoSans';
```

