# Ethereum Kickstarter
This project emulates the functionality of popular website Kickstarter but makes the entire funding process decentralized. The ethereum/contracts directory contains a factory
contract that can be used to create an arbitrary number of funding campaigns for different start-ups. Anyone with a valid ethereum address can contribute to a deployed campaign
smart contract provided that their contribution is above the minimum contribution limit. Additionally, if the owner of a campaign wants to spend contribution funds, he/she must 
obtain approval from the majority of contributors. Contributors must independently vote on each spending request. This voting system holds campaign owners accountable for the money they spend and prevents scams common to traditional funding platforms.
Functional tests using the mocha framework are located in the test directory. This project is based off of Stephen Grider's Ethereum Udemy course.
