To run one of our files:
    Use terminal or command line:
        php folder/filename.php
        (paste this into command line: 
            php tests/main.php
            php tests/validity.php
        )
The blockchain will print out in a JSON format for readability.

You can tweak the for-loop in main.php to your liking, however this is NOT how
it will ultimately operate. We will be taking in transactions real-time and use that to
populate the blockchain. 

Our isValid() function would be set on an interval (probably VERY often), alerting
us to any discrepencies or tampering with data.

