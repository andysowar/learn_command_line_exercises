### Do More

In the tmp directory:

1.

`mkdir stuff`

`mkdir stuff/things`

`mkdir stuff/things/john`

`mkdir stuff/things/alex`

`mkdir stuff/things/alex/bilbo`

`mkdir stuff/things/alex/bilbo/timmy`

`mkdir stuff/things/alex/bilbo/timmy/hank`

`mkdir stuff/things/alex/bilbo/timmy/hank/frank`

`mkdir stuff/things/alex/bilbo/timmy/hank/frank/sam`

`mkdir stuff/things/alex/bilbo/timmy/hank/frank/sam/ralph`

`mkdir stuff/things/alex/bilbo/timmy/hank/frank/sam/ralph/monkey`

`mkdir stuff/things/alex/bilbo/timmy/hank/frank/sam/ralph/monkey/dog`

`mkdir stuff/things/alex/bilbo/timmy/hank/frank/sam/ralph/monkey/dog/cow`

`mkdir stuff/things/alex/bilbo/timmy/hank/frank/sam/ralph/monkey/dog/cow/moo`

`mkdir stuff/things/alex/bilbo/timmy/hank/frank/sam/ralph/monkey/dog/cow/moo/chicken`

`mkdir stuff/things/alex/bilbo/timmy/hank/frank/sam/ralph/monkey/dog/cow/moo/chicken/beer`

`mkdir stuff/things/alex/bilbo/timmy/hank/frank/sam/ralph/monkey/dog/cow/moo/chicken/beer/table`

`mkdir stuff/things/alex/bilbo/timmy/hank/frank/sam/ralph/monkey/dog/cow/moo/chicken/beer/table/candle`

`mkdir stuff/things/alex/bilbo/timmy/hank/frank/sam/ralph/monkey/dog/cow/moo/chicken/beer/table/candle/lamp`

`mkdir stuff/things/alex/bilbo/timmy/hank/frank/sam/ralph/monkey/dog/cow/moo/chicken/beer/table/candle/lamp/twenty`

`cd stuff/things/alex/bilbo/timmy/hank/frank/sam/ralph/monkey/dog/cow/moo/chicken/beer/table/candle/lamp/twenty`

`cd ..`

`rmdir twenty`

`cd ..`

`rmdir lamp`

`cd ..`

`rmdir candle`

`cd ..`

`rmdir table`

`cd ..`

`rmdir beer`

`cd ..`

`rmdir chicken`

`cd ..`

`rmdir moo`

`cd ..`

`rmdir cow`

`cd ..`

`rmdir dog`

`cd ..`

`rmdir monkey`

`cd ..`

`rmdir ralph`

`cd ..`

`rmdir sam`

`cd ..`

`rmdir frank`

`cd ..`

`rmdir hank`

`cd ..`

`rmdir timmy`

`cd ..`

`rmdir bilbo`

`cd ..`

`rmdir alex`

`cd ..`

`rmdir john`

`cd ..`

`rmdir things`

`cd ..`

`rmdir stuff`

`cd ..`

2.

`mkdir -p stuff/things/john/alex/bilbo/timmy/hank/frank/sam/ralph`

` cd stuff/things/john/alex/bilbo/timmy/hank/frank/sam/ralph`

` cd ..`

`rmdir ralph`

`cd ..`

`rmdir sam`

`cd ..`

`rmdir frank`

`cd ..`

`rmdir hank`

`cd ..`

`rmdir timmy`

`cd ..`

`rmdir bilbo`

`cd ..`

`rmdir alex`

`cd ..`

`rmdir john`

`cd ..`

`rmdir things`

`cd ..`

`rmdir stuff`

`cd ..`


### English Questions

######1. Can you remove the tmp directory?

Not unless it's empty! After removing all of the directories inside of tmp with `rmdir <file>`, `cd` one level up & type `rmdir tmp`

######2. Let's remove the tmp directory.

No problem! After removing all directories inside of tmp with `rmdir <file>` make sure you're in `/homework/chapter_7` & type `rmdir tmp`.

