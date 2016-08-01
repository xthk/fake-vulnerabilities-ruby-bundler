# Fake vulnerabilities ruby/bundler

Example repository containing fake data with vulnerable dependencies

This repository fakes at least the dependencies found in bundle-audit.log

    $ bundle-audit | head
    Name: actionpack
    Version: 4.1.0
    Advisory: CVE-2014-0130
    Criticality: Medium
    URL: https://groups.google.com/forum/#!topic/rubyonrails-security/NkKc7vTW70o
    Title: Directory Traversal Vulnerability With Certain Route Configurations
    Solution: upgrade to ~> 3.2.18, ~> 4.0.5, >= 4.1.1
    
    Name: actionpack
    Version: 4.1.0
