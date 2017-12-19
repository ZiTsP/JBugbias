# JBugbias

Now, developing in develop branch

## (Develop) Attention

Pictures or configure files (which are included in a jar package) are put into dirs `/src/main/resources/` and `/src/test/resources/`.  
If there are not these `resources` dirs, execute gradle-task

```bash
$ gradle initDirs
```

## (Develop) Software Artifacts (Plan)

(Develop-Priority : Hight to Low)

- JBugbias-EclipsePlugin (gui : swt)
    - For eclipse-plugin
- JBugbias-Application (gui : awt)
    - For gui application
- JBugbias-Console
    - For command line
- JBugbias-Minimal
    - for server (Extends JBugbias-Console)
