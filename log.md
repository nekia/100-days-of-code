# 100 Days Of Code - Log

Create an application for sharing transcript working on browser with using Rust language.

### Day 0: April 4, 2019

**Today's Progress**: Create a Rust file to try a simple key rotation with Indy SDK.

**Thoughts:** I really struggled with understanding Rust syntax because it's quite new language for me.

**Link to work:** [Git: RustExercises Repo](https://github.com/nekia/RustExercises/commit/56133344061f0c80da10e77d5cfbeff402d87470)

### Day 1: April 5, 2019

**Today's Progress**: Spend the most of time to setup Rust development env

**Thoughts:** It might be difficult to make use this one hour only for purely coding until settling in this activity.

### Day 2: April 8, 2019

**Today's Progress**: Code Scaffolding code that likely to appear in anything that uses indy. But it doesn't work on my environment. I have some error.

**Thoughts:** Once an error happen, the state of the environment seems to be left unexpected, I think. I need to understand how to clean up my env

### Day 3: April 9, 2019

**Today's Progress**: Done debug for my first Rust exercise. Now it works successfull without any errors. Good!

**Thoughts:** At the same time with this activity, I might have better take some classes for Rust in Udemy.

**Link to work:** [Debug log](https://github.com/nekia/100-days-of-code/issues/1#issuecomment-481028271)

### Day 4: April 10, 2019

**Today's Progress**: Stuck in the key rotation. I likely use obsoleted APIs in my code.

**Thoughts:** I need to change the reference to be read for writing my first project code.

**Link to work:** [Git: RustExercises Repo](https://github.com/nekia/RustExercises/commit/9bf3b72b022aae737c9f0ddfcb32dc35de9a9ad5)

### Day 5: April 11, 2019

**Today's Progress**: I could update all the obsoleted APIs to new ones and see that the application worked properly.

**Thoughts:** I can't find out where the wallet data is stored on my environment. It's quite inefficient that I have to increment wallet name and pool name every time I run my application.

**Link to work:** [Git: RustExercises Repo](https://github.com/nekia/RustExercises/commit/496cbcf20b01aae28a45dcfcd5e384f69e6249c6)

### Day 6: April 15, 2019

**Today's Progress**: I've completed to code for issueing a credential.

**Thoughts:** Time really flies during this one hour every day.

**Link to work:** [Git: RustExercises Repo](https://github.com/nekia/RustExercises/commit/2aa5f092ed86cc25d43e21933760377f0ed35d7b)

### Day 7: April 16, 2019

**Today's Progress**: I've completed to code for issueing a proof. I've already gone through the common processes for Self Soverign Identity (SSI) management with Rust language.

**Thoughts:** I'll start my personal development project using SSI mgmt!

**Link to work:** [Git: RustExercises Repo](https://github.com/nekia/RustExercises/commit/737eb3535e0952fcc1e036242b4a68382c8edbbe)

### Day 8: April 22, 2019 (behind 10days)

**Today's Progress**: I've found out that there is another way to implement my own application on indy network. I understood that, by using indy-agent (higher-level component than indy-sdk for accessing indy network) we are able to manage all of the DIDs which are created between all the relationships easily.

**Thoughts:** I had caught a cold for the recent a few days. Managing my own health is also one of the important things to achieve this challenge until the 100th day.

**Link to work:** [Activity Log](https://github.com/nekia/100-days-of-code/issues/3#issuecomment-485410580)

### Day 9: April 23, 2019 (behind 10days)

**Today's Progress**: I spent all the time to read the code of indy-agent sample. It consists of message handler written by python(backend) and GUI(Vue.js). 

**Thoughts:** I'm going to start with the enhancement of this sample tha  is toadd the interoperation with indy-pool.

**Link to work:** [Source code: reference](https://github.com/hyperledger/indy-agent/tree/master/python)
