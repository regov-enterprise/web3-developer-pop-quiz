<p align="center"> 
    <img src="https://regov-store.s3.ap-southeast-1.amazonaws.com/REGOV+Logo_CMYK.png" width="200" >
</p>

<p style="text-align: center;"> Engineering PopQuiz! </p>

Choose any one of the following questions

## Question 1 (Three Questions)

1. > Given the head of a linked list, return the list after sorting it in ascending order.

<p align="Left"> 
    <img src="https://regov-store.s3.ap-southeast-1.amazonaws.com/link-list.png" >
</p>

**E.g:**
`Input: head = [4,2,1,3]`
`Output: [1,2,3,4]`

`Input: head = [-1,5,3,4,0]`
`Output: [-1,0,3,4,5]`

**Constraints:**

- The number of nodes in the list is in the range `[0, 5 * 104]`.

- `-105 <= Node.val <= 105`

**Follow up:** Can you sort the linked list in `O(n logn)` time and `O(1)` memory (i.e. constant space)?

2. 
> You are given an array of strings tokens that represents an arithmetic expression in a Reverse Polish Notation.

> Evaluate the expression. Return an integer that represents the value of the expression.

*** Note that: ***
- The valid operators are '+', '-', '*', and '/'.
- Each operand may be an integer or another expression.
- The division between two integers always truncates toward zero.
- There will not be any division by zero.
- The input represents a valid arithmetic expression in a reverse polish notation.
- The answer and all the intermediate calculations can be represented in a 32-bit integer.

**E.g 1:**

Input: tokens = ["4","2","+","5","*"]
Output: 30
Explanation: ((4 + 2) * 5) = 30

**E.g 2:**
Input: tokens = ["4","13","5","/","+"]
Output: 6
Explanation: (4 + (13 / 5)) = 6


**Constraints:**

`1 <= tokens.length <= 104`
`tokens[i] is either an operator: "+", "-", "*", or "/", or an integer in the range [-200, 200].`


3. Maximum Product Subarray

Given an integer array nums, find a subarray that has the largest product, and return the product.

The test cases are generated so that the answer will fit in a 32-bit integer.

**E.g 1:**
`Input: nums = [2,3,-2,4]`
`Output: 6`
`Explanation: [2,3] has the largest product 6.`

**E.g 1:**
`Input: nums = [-2,0,-1]`
`Output: 0`
`Explanation: The result cannot be 2, because [-2,-1] is not a subarray.`

**Constraints:**

- `1 <= nums.length <= 2 * 104`
- `-10 <= nums[i] <= 10`
- `The product of any prefix or suffix of nums is guaranteed to fit in a 32-bit integer.`

## Question 2 (One Question)

**Web3 Identity Application**

<p> Develop a basic Web3 Identity solution called WPOP. The WPOP is intended to demonstrated workflow of Verifiable Credentials and its inhernet workflows on a basic level.<p/>

<p> WPOP should have Seven key capabilities: </p>
 - Ability to connect on a local Indy node or any Web3 Identity capable Node
 - Ability to connect two users key actors( An user that issue credentials and another that holds credentials) 
 - Ability to simulate Credentials Issuance and Verification feature
 - Ability to list credentials existing in a wallet
 - Registration
 - Login & Logout

 <p> Implementation expecations : </p>
 - WPOP is an ResfFul API based application. 
 - WPOP is a completely dockerized application
 - Dockerize a local Indy network / Connect to any available test network
 - WPOP has clear instruction in the README on how to run the app locally
 - WPOP APIs should have clearly written comments on the code implementation


<p> Reference study materials: the W3C consortium published guidelines for implementing SSI based on the concepts of Verifiable Credentials (VC) and the Decentralized Identity (DID) models.  </p>

 - [W3C VC Credentials] (https://www.w3.org/TR/vc-data-model/)
 - [W3C DID] (https://www.w3.org/TR/did-core/)

 ## Points to note
  - This pop quiz will enable us to assess your work quality and documentation for a real project
  - Kindly produce concise/short documents: quality over quantity. You are not required to produce any work that would take beyond the target dates for submission
  - For any queries, reach out to the emails below

# Submission process

1. Email your work to techchallenge@regovtech.com

Good Luck!# web3-developer-pop-quiz
