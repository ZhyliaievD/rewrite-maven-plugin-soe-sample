Sample project to reproduce StackOverflowError issue https://github.com/openrewrite/rewrite-maven-plugin/issues/756

Run `mvn -U org.openrewrite.maven:rewrite-maven-plugin:run -Drewrite.activeRecipes=org.openrewrite.java.RemoveUnusedImports` to reproduce the issue.

