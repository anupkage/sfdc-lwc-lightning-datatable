Contribution Guidelines

* Identifying or setting Engineering standards
    * small as variable naming conventions
        * General
            * Names to be meaningful
        * Classes
            * try to avoid ‘name collisions’ ie: NotificationManager - this collides with a system provided class
            * Must be meaningful. 
            * No classes named Test.
            * conventions?
                * Test classes for instance, CLASSNAMETest
            * One test class per class
            * for Visualforce
                * controller vfpageController
                * extension vfpageExtension
        * Variables
            * variable name have to be at least 3 characters
            * should be descriptive
            * 
        * Methods
            * start with a verb?
    * extend into testing
        * Tests have to exist
        * Tests have to pass before merge
        * Test all logical paths, nulls, empty strings, lists, collections.
        * feature pressure can delay test development, so tests are part of the feature!
        * if you can test it, you should. 
    * comments!
        *  YES write comments. write WHY comments, not what?
    * code smells
    * code length
        * Standard is loose - based on methods should do one thing. 
        * is it testable? does the method name make sense? does it do one thing?
        * Rule of 9? 9 lines in a method, 9 methods in a class etc. 
        * Heuristics:
            * methods should fit on one screen
            * classes - should be focused on one thing
                * order of info in a class: Class variables, constants, and Constructors, then public then private methods
        * Simplifying conditionals and code length
    * code quality
    * no features without tests
    * peer review? / code review
        * No one likes to hear their baby’s ugly
    * Per project?
    * a standard is a foundation for the project: applied at beginning, or retroactively
    * What can be automated, standards wise?
        * Tooling: PMD, Prettier, etc.
    * Can be revisited / refactored, but not necessarily mid-work.
    * Laying them out vs. enforcing.

      Credit :  https://quip.com/ViKfAetuWBir
