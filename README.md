# Webdriver.io-with-mocha-and-chai
My own E2E webpage automation testing project example with Webdriver.io,mocha and chai automation frameworks
Quick setup:
1) Extract the rar file to any location on your computer
2) Go into the extracted folder 'webdriverio-test' and run in the terminal 'npm install' to install all project dependencies (see  package.json file)
3) Type in the terminal 'npm test' to start running the tests
4) Define whith tests to run in /wdio.conf.js' configuration file e.g.
suites: {
        siteSanityExamples: [
            
              './test/specs/siteAutomation_example1.js',
              './test/specs/siteAutomation_example2.js',
        ],
        
