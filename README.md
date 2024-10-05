# https://github.com/sbt/sbt/issues/7722

```
[info] welcome to sbt 2.0.0-M2 (Eclipse Adoptium Java 21.0.4)
[info] loading project definition from /home/runner/work/sbt-2-console-project-bug/sbt-2-console-project-bug/project
[info] set current project to sbt-2-console-project-bug (in build file:/home/runner/work/sbt-2-console-project-bug/sbt-2-console-project-bug/)
[info] Non-compiled module 'scala3-sbt-bridge' for Scala 3.3.3. Compiling...
-- [E006] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/Action.java:5:37 -
5 |final public class Action implements xsbti.Action {
  |                                     ^^^^^
  |                                     Not found: xsbti
  |
  | longer explanation available when compiling with `-explain`
-- [E006] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/WorkspaceEdit.java:7:44 
7 |final public class WorkspaceEdit implements xsbti.WorkspaceEdit {
  |                                            ^^^^^
  |                                            Not found: xsbti
  |
  | longer explanation available when compiling with `-explain`
-- [E008] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/CompilerBridge.java:8:13 
8 |import xsbti.AnalysisCallback;
  |             ^
  |         value xsbti is not a member of <root> - did you mean _root_.xsbt?
-- [E008] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/CompilerBridge.java:9:13 
9 |import xsbti.Logger;
  |             ^
  |         value xsbti is not a member of <root> - did you mean _root_.xsbt?
-- [E008] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/CompilerBridge.java:10:13 
10 |import xsbti.Reporter;
   |             ^
   |       value xsbti is not a member of <root> - did you mean _root_.xsbt?
-- [E008] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/CompilerBridge.java:11:13 
11 |import xsbti.VirtualFile;
   |             ^
   |       value xsbti is not a member of <root> - did you mean _root_.xsbt?
-- [E008] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/CompilerBridge.java:12:21 
12 |import xsbti.compile.CompileProgress;
   |                     ^
   |       value xsbti is not a member of <root> - did you mean _root_.xsbt?
-- [E008] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/CompilerBridge.java:13:21 
13 |import xsbti.compile.CompilerInterface2;
   |                     ^
   |       value xsbti is not a member of <root> - did you mean _root_.xsbt?
-- [E008] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/CompilerBridge.java:14:21 
14 |import xsbti.compile.DependencyChanges;
   |                     ^
   |       value xsbti is not a member of <root> - did you mean _root_.xsbt?
-- [E008] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/CompilerBridge.java:15:21 
15 |import xsbti.compile.Output;
   |                     ^
   |       value xsbti is not a member of <root> - did you mean _root_.xsbt?
-- [E008] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/CompilerBridgeDriver.java:21:13 
21 |import xsbti.Problem;
   |             ^
   |       value xsbti is not a member of <root> - did you mean _root_.xsbt?
-- [E008] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/CompilerBridgeDriver.java:22:13 
22 |import xsbti.*;
   |             ^
   |       value xsbti is not a member of <root> - did you mean _root_.xsbt?
-- [E008] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/CompilerBridgeDriver.java:23:21 
23 |import xsbti.compile.Output;
   |                     ^
   |       value xsbti is not a member of <root> - did you mean _root_.xsbt?
-- [E008] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/DelegatingReporter.java:19:13 
19 |import xsbti.Position;
   |             ^
   |       value xsbti is not a member of <root> - did you mean _root_.xsbt?
-- [E008] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/DelegatingReporter.java:20:13 
20 |import xsbti.Severity;
   |             ^
   |       value xsbti is not a member of <root> - did you mean _root_.xsbt?
-- [E006] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/DelegatingReporter.java:33:28 
33 |  public DelegatingReporter(xsbti.Reporter delegate, Function<SourceFile, String> lookupVirtualFileId) {
   |                            ^^^^^
   |                            Not found: xsbti
   |
   | longer explanation available when compiling with `-explain`
-- [E006] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/DelegatingReporter.java:26:10 
26 |  private xsbti.Reporter delegate;
   |          ^^^^^
   |          Not found: xsbti
   |
   | longer explanation available when compiling with `-explain`
-- [E006] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/DiagnosticCode.java:5:45 
5 |final public class DiagnosticCode implements xsbti.DiagnosticCode {
  |                                             ^^^^^
  |                                             Not found: xsbti
  |
  | longer explanation available when compiling with `-explain`
-- [E006] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/FallbackVirtualFile.java:14:41 
14 |public class FallbackVirtualFile extends xsbti.BasicVirtualFileRef implements xsbti.VirtualFile {
   |                                         ^^^^^
   |                                         Not found: xsbti
   |
   | longer explanation available when compiling with `-explain`
-- [E006] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/FallbackVirtualFile.java:14:78 
14 |public class FallbackVirtualFile extends xsbti.BasicVirtualFileRef implements xsbti.VirtualFile {
   |                                                                              ^^^^^
   |                                                        Not found: xsbti
   |
   | longer explanation available when compiling with `-explain`
-- [E006] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/FallbackPathBasedFile.java:10:74 
10 |public class FallbackPathBasedFile extends FallbackVirtualFile implements xsbti.PathBasedFile {
   |                                                                          ^^^^^
   |                                                        Not found: xsbti
   |
   | longer explanation available when compiling with `-explain`
-- [E006] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/IncrementalCallback.java:11:29 
11 |  public IncrementalCallback(xsbti.AnalysisCallback delegate, Function<SourceFile, xsbti.VirtualFile> asVirtualFile) {
   |                             ^^^^^
   |                             Not found: xsbti
   |
   | longer explanation available when compiling with `-explain`
-- [E006] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/IncrementalCallback.java:11:83 
11 |  public IncrementalCallback(xsbti.AnalysisCallback delegate, Function<SourceFile, xsbti.VirtualFile> asVirtualFile) {
   |                                                                                   ^^^^^
   |                                                        Not found: xsbti
   |
   | longer explanation available when compiling with `-explain`
-- [E006] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/IncrementalCallback.java:8:16 
8 |  private final xsbti.AnalysisCallback delegate;
  |                ^^^^^
  |                Not found: xsbti
  |
  | longer explanation available when compiling with `-explain`
-- [E006] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/IncrementalCallback.java:9:37 
9 |  private final Function<SourceFile, xsbti.VirtualFile> asVirtualFile;
  |                                     ^^^^^
  |                                     Not found: xsbti
  |
  | longer explanation available when compiling with `-explain`
-- [E006] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/IncrementalCallback.java:17:41 
17 |  public void api(SourceFile sourceFile, xsbti.api.ClassLike classApi) {
   |                                         ^^^^^
   |                                         Not found: xsbti
   |
   | longer explanation available when compiling with `-explain`
-- [E006] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/IncrementalCallback.java:37:72 
37 |  public void usedName(String className, String name, java.util.EnumSet<xsbti.UseScope> useScopes) {
   |                                                                        ^^^^^
   |                                                        Not found: xsbti
   |
   | longer explanation available when compiling with `-explain`
-- [E006] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/IncrementalCallback.java:42:140 
42 |  public void binaryDependency(java.nio.file.Path onBinaryEntry, String onBinaryClassName, String fromClassName, SourceFile fromSourceFile, xsbti.api.DependencyContext context) {
   |                                                                                                                                            ^^^^^
   |                                                        Not found: xsbti
   |
   | longer explanation available when compiling with `-explain`
-- [E006] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/IncrementalCallback.java:47:74 
47 |  public void classDependency(String onClassName, String sourceClassName, xsbti.api.DependencyContext context) {
   |                                                                          ^^^^^
   |                                                        Not found: xsbti
   |
   | longer explanation available when compiling with `-explain`
-- [E008] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/InterfaceCompileFailed.java:6:13 
6 |import xsbti.Problem;
  |             ^
  |         value xsbti is not a member of <root> - did you mean _root_.xsbt?
-- [E006] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/InterfaceCompileFailed.java:8:44 
8 |public class InterfaceCompileFailed extends xsbti.CompileFailed {
  |                                            ^^^^^
  |                                            Not found: xsbti
  |
  | longer explanation available when compiling with `-explain`
-- [E006] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/OldIncrementalCallback.java:14:32 
14 |  public OldIncrementalCallback(xsbti.AnalysisCallback delegate) {
   |                                ^^^^^
   |                                Not found: xsbti
   |
   | longer explanation available when compiling with `-explain`
-- [E006] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/OldIncrementalCallback.java:12:16 
12 |  private final xsbti.AnalysisCallback delegate;
   |                ^^^^^
   |                Not found: xsbti
   |
   | longer explanation available when compiling with `-explain`
-- [E006] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/OldIncrementalCallback.java:26:41 
26 |  public void api(SourceFile sourceFile, xsbti.api.ClassLike classApi) {
   |                                         ^^^^^
   |                                         Not found: xsbti
   |
   | longer explanation available when compiling with `-explain`
-- [E006] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/OldIncrementalCallback.java:48:72 
48 |  public void usedName(String className, String name, java.util.EnumSet<xsbti.UseScope> useScopes) {
   |                                                                        ^^^^^
   |                                                        Not found: xsbti
   |
   | longer explanation available when compiling with `-explain`
-- [E006] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/OldIncrementalCallback.java:54:140 
54 |  public void binaryDependency(java.nio.file.Path onBinaryEntry, String onBinaryClassName, String fromClassName, SourceFile fromSourceFile, xsbti.api.DependencyContext context) {
   |                                                                                                                                            ^^^^^
   |                                                        Not found: xsbti
   |
   | longer explanation available when compiling with `-explain`
-- [E006] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/OldIncrementalCallback.java:59:74 
59 |  public void classDependency(String onClassName, String sourceClassName, xsbti.api.DependencyContext context) {
   |                                                                          ^^^^^
   |                                                        Not found: xsbti
   |
   | longer explanation available when compiling with `-explain`
-- [E008] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/PositionBridge.java:11:13 
11 |import xsbti.Position;
   |             ^
   |       value xsbti is not a member of <root> - did you mean _root_.xsbt?
-- [E008] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/Problem.java:17:13 
17 |import xsbti.Position;
   |             ^
   |       value xsbti is not a member of <root> - did you mean _root_.xsbt?
-- [E008] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/Problem.java:18:13 
18 |import xsbti.Severity;
   |             ^
   |       value xsbti is not a member of <root> - did you mean _root_.xsbt?
-- [E008] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/Problem.java:19:13 
19 |import xsbti.VirtualFile;
   |             ^
   |       value xsbti is not a member of <root> - did you mean _root_.xsbt?
-- [E006] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/Problem.java:22:38 
22 |final public class Problem implements xsbti.Problem {
   |                                      ^^^^^
   |                                      Not found: xsbti
   |
   | longer explanation available when compiling with `-explain`
-- [E006] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/Problem.java:67:18 
67 |  public Optional<xsbti.DiagnosticCode> diagnosticCode() {
   |                  ^^^^^
   |                  Not found: xsbti
   |
   | longer explanation available when compiling with `-explain`
-- [E006] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/Problem.java:83:14 
83 |  public List<xsbti.Action> actions() {
   |              ^^^^^
   |              Not found: xsbti
   |
   | longer explanation available when compiling with `-explain`
-- [E008] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/TextEdit.java:3:13 
3 |import xsbti.Position;
  |             ^
  |         value xsbti is not a member of <root> - did you mean _root_.xsbt?
-- [E006] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/TextEdit.java:5:39 
5 |final public class TextEdit implements xsbti.TextEdit {
  |                                       ^^^^^
  |                                       Not found: xsbti
  |
  | longer explanation available when compiling with `-explain`
-- [E008] Not Found Error: /tmp/sbt_8a7f4aac/dotty/tools/xsbt/WorkspaceEdit.java:5:13 
5 |import xsbti.TextEdit;
  |             ^
  |         value xsbti is not a member of <root> - did you mean _root_.xsbt?
-- [E008] Not Found Error: /tmp/sbt_8a7f4aac/xsbt/CachedCompilerImpl.java:6:13 -
6 |import xsbti.*;
  |             ^
  |         value xsbti is not a member of <root> - did you mean _root_.xsbt?
-- [E008] Not Found Error: /tmp/sbt_8a7f4aac/xsbt/CachedCompilerImpl.java:7:21 -
7 |import xsbti.compile.*;
  |                     ^
  |         value xsbti is not a member of <root> - did you mean _root_.xsbt?
-- [E008] Not Found Error: /tmp/sbt_8a7f4aac/xsbt/CompilerInterface.java:6:13 --
6 |import xsbti.AnalysisCallback;
  |             ^
  |         value xsbti is not a member of <root> - did you mean _root_.xsbt?
-- [E008] Not Found Error: /tmp/sbt_8a7f4aac/xsbt/CompilerInterface.java:7:13 --
7 |import xsbti.Logger;
  |             ^
  |         value xsbti is not a member of <root> - did you mean _root_.xsbt?
-- [E008] Not Found Error: /tmp/sbt_8a7f4aac/xsbt/CompilerInterface.java:8:13 --
8 |import xsbti.Reporter;
  |             ^
  |         value xsbti is not a member of <root> - did you mean _root_.xsbt?
-- [E008] Not Found Error: /tmp/sbt_8a7f4aac/xsbt/CompilerInterface.java:9:21 --
9 |import xsbti.compile.*;
  |                     ^
  |         value xsbti is not a member of <root> - did you mean _root_.xsbt?
-- [E008] Not Found Error: /tmp/sbt_8a7f4aac/xsbt/ConsoleInterface.java:10:13 --
10 |import xsbti.Logger;
   |             ^
   |       value xsbti is not a member of <root> - did you mean _root_.xsbt?
-- [E008] Not Found Error: /tmp/sbt_8a7f4aac/xsbt/DottydocRunner.java:6:13 -----
6 |import xsbti.Logger;
  |             ^
  |         value xsbti is not a member of <root> - did you mean _root_.xsbt?
-- [E008] Not Found Error: /tmp/sbt_8a7f4aac/xsbt/DottydocRunner.java:7:13 -----
7 |import xsbti.Severity;
  |             ^
  |         value xsbti is not a member of <root> - did you mean _root_.xsbt?
-- [E006] Not Found Error: /tmp/sbt_8a7f4aac/xsbt/DottydocRunner.java:28:52 ----
28 |  public DottydocRunner(String[] args0, Logger log, xsbti.Reporter delegate) {
   |                                                    ^^^^^
   |                                                    Not found: xsbti
   |
   | longer explanation available when compiling with `-explain`
-- [E006] Not Found Error: /tmp/sbt_8a7f4aac/xsbt/DottydocRunner.java:26:16 ----
26 |  private final xsbti.Reporter delegate;
   |                ^^^^^
   |                Not found: xsbti
   |
   | longer explanation available when compiling with `-explain`
-- [E008] Not Found Error: /tmp/sbt_8a7f4aac/xsbt/ScaladocInterface.java:6:13 --
6 |import xsbti.Logger;
  |             ^
  |         value xsbti is not a member of <root> - did you mean _root_.xsbt?
-- [E008] Not Found Error: /tmp/sbt_8a7f4aac/xsbt/ScaladocInterface.java:7:13 --
7 |import xsbti.Reporter;
  |             ^
  |         value xsbti is not a member of <root> - did you mean _root_.xsbt?
-- [E006] Not Found Error: /tmp/sbt_8a7f4aac/xsbt/ScaladocInterface.java:10:45 -
10 |  public void run(String[] args, Logger log, xsbti.Reporter delegate) {
   |                                             ^^^^^
   |                                             Not found: xsbti
   |
   | longer explanation available when compiling with `-explain`
61 errors found
[info] Attempting to fetch org.scala-lang:scala3-sbt-bridge:3.3.3.
[error] (consoleProject) Error compiling the sbt component 'scala3-sbt-bridge'
[error] elapsed time: 7 s
```
