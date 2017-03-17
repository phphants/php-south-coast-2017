---
name: Nikita Popov
ref: popov
avatar: nikita_popov.jpg
twitter: nikita_ppv
bio: >
    PHP core developer and one of the primary contributors to PHP 7. Studying computer science and theoretical physics
    at TU Berlin.
talks:
  talk1:
    title: Static Optimization of PHP Bytecode
    abstract: >
        The PHP compiler turns PHP code into "opcodes", which are then executed on the Zend Virtual Machine. To improve
        performance, it is possible to optimize these opcodes prior to execution. PHP 7.1 introduces a sophisticated
        opcode optimization infrastructure, which uses static single assignment (SSA) form and type inference to enable
        more advanced optimizations.
        
        
        An example: Normally, an "add $a, $b" instruction first has to check the types of $a and $b, to determine
        whether to perform an integer addition, or a floating point addition, or maybe even an array or GMP addition.
        However, if we can statically determine that $a and $b are integers, we can use a special "add_int $a, $b"
        instruction, which does not perform these type checks and thus improves performance. Because PHP is very
        dynamic, doing this is harder than it may sound...
        
        
        This talk introduces the new optimization infrastructure, the optimizations based on it, and discusses which
        parts of the PHP language are particularly hostile to this form of optimization. This is an advanced talk, but I
        will try to present the topic in a way that does not require a strong compiler construction background.
    type: regular
---
