# Draw-the-tree-of-processes
main()
{
int i;
int n;
pid_t childpid;
n = 3;
for (i = 1; i <= n; ++i) {
childpid = fork();
if (childpid == 0) break;
}
printf(ā%dā, i);
}
