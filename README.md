<pre>
SIZZLEUNRLSD(1)             Developer Manual             SIZZLEUNRLSD(1)

NAME
       SizzleUnrlsd - Hugo Payet, builds program analysis tools on LLVM

SYNOPSIS
       sizzleunrlsd [--static] [--dyn] [--sym]

DESCRIPTION
       Creator and lead developer of <a href="https://github.com/CoreTrace">CoreTrace</a>, an open-source
       toolchain that takes source code to actionable evidence:
       static analysis, runtime instrumentation and CI-ready
       reports. Started with C/C++, now extending to Python and
       other languages.

       Compiler infrastructure
              Clang/LLVM internals: LLVM IR, passes, LibTooling,
              instrumentation pipelines.

       Static analysis
              Stack and memory safety, concurrency, undefined
              behavior. Cross-TU reasoning, symbolic execution,
              SMT-backed checks.

       Runtime analysis
              Shadow memory, allocation and bounds tracking,
              call and vtable tracing.

       Performance
              Parallel pipelines and SCC worklist algorithms:
              -30% median analysis time, measured.

       Systems
              Low-level C and x86 assembly. Wrote a <a href="https://github.com/SizzleUnrlsd/TekSH">shell</a> and a
              <a href="https://github.com/SizzleUnrlsd/GarbageCollector">garbage collector</a> from scratch. Soft spot for
              embedded and resource-constrained targets.

LANGUAGES
       C, C++, Python, x86 assembly, TypeScript, Rust

ACTIVITY
       4,684 contributions in the last year

SEE ALSO
       <a href="https://github.com/CoreTrace/coretrace">coretrace</a>(1), <a href="https://github.com/CoreTrace/coretrace-compiler">coretrace-compiler</a>(1),
       <a href="https://github.com/CoreTrace/coretrace-stack-analyzer">coretrace-stack-analyzer</a>(1),
       <a href="https://github.com/CoreTrace/coretrace-concurrency-analyzer">coretrace-concurrency-analyzer</a>(1),
       <a href="https://github.com/CoreTrace/coretrace-runtime-analyzer">coretrace-runtime-analyzer</a>(1),
       <a href="https://github.com/CoreTrace/coretrace-python-analyzer">coretrace-python-analyzer</a>(1)

CONTACT
       <a href="mailto:hugo.payet@epitech.eu">hugo.payet@epitech.eu</a>
       <a href="https://www.linkedin.com/in/hugo-payet00">linkedin.com/in/hugo-payet00</a>
       <a href="https://coretrace.fr">coretrace.fr</a>
</pre>
