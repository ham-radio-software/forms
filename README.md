# D-Rats Forms

Forms used by D-Rats and possibly other programs.

These forms consist of XML file describing the form and an optional XSL for a
style sheet for the form.

This is planned to allow D-Rats users to periodically update their forms.

Advanced maintainers can copy the tests/pre-commit script to inside of the
.git/hooks directory which if the proper tools are installed, will test the
format of the files in a git commit action.  This requires shellcheck,
yamllint, and codespell to be installed.
