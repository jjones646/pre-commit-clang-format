# ClangFormat hook for pre-commit

[ClangFormat](http://clang.llvm.org/docs/ClangFormat.html) package for [pre-commit](http://pre-commit.com).

## Using clang-format with pre-commit

```yaml
-   repo: https://github.com/jjones646/pre-commit-clang-format
    rev: master
    hooks:
    -   id: clang-format
```
