<p align="center"> 
    <img src="https://regov-store.s3.ap-southeast-1.amazonaws.com/REGOV+Logo_CMYK.png" width="200" >
</p>

<p style="text-align: center;"> Engineering PopQuiz! </p>

Four questions Answer one Algorithm and one Programming

## Outcome
1. Spin up a local Indy network (Dockerised)
2. Connect the Indy with Issuer Agent
3. Create three agents with the Acapy and exposed enpoints on Swagger based documentation (Dockerised)
- Create a Holder APIs with the following capability
- Register on the app
- Login & Logout
- Request Credentials
- Store Credentials
- View credentials
- Present Credentials



2. Given the head of a linked list, return the list after sorting it in ascending order.

<p align="Left"> 
    <img src="https://regov-store.s3.ap-southeast-1.amazonaws.com/link-list.png" >
</p>

**Example:**
Input: head = [4,2,1,3]
Output: [1,2,3,4]

Input: head = [-1,5,3,4,0]
Output: [-1,0,3,4,5]

**Constraints:**

- The number of nodes in the list is in the range [0, 5 * 104].

- -105 <= Node.val <= 105

**Follow up:** Can you sort the linked list in O(n logn) time and O(1) memory (i.e. constant space)?

Aries Agent
3. Agent should be able to issue credentials
## Rationale

<p> The Internet has a weak link that is long overdue for a complete overhaul. It is considered unfashionable as modern software continues to use the same centralized databases and cannot guarantee its safety. Most databases are usually located in a central location and owned by a single authority. </br> Hence, they own and control all the records in their servers. In other words, a user's personal and confidential information used for registration on any online platform is actually at the mercy of the platform owners. <p/>

<p> This has caused unimaginable risk to users worldwide, particularly the cases of global hacks and data breaches on banks and financial institutions. </br> Even more, personal data loss for anyone increases the risks of identity theft or infringement on many fronts: health, finances, business and many personal endeavours. <p/>

<p> Web3.0 is a paradigm shift from the current internet, considered Web2.0. </br> It intends to give users absolute control over their personal information on the internet. Companies will no longer be able to control the personal data on their online platforms, nor will they have the explicit authority to share, extract or manipulate them. Users will have complete ownership of their data, a mantra culminating in the Self-sovereign Identity (SSI) blockchain. SSI powers the Web3.0 revolution. The paradigm shift gives rise to the adoption of SSI identity by many companies and service providers. The transition from a central to a decentralized identity model powered by SSI is the base of new projects. <p/>

<p> As an open-source initiative, the W3C consortium published guidelines for implementing SSI based on the concepts of Verifiable Credentials (VC) and the Decentralized Identity (DID) models.  </p>

 - [W3C VC Credentials] (https://www.w3.org/TR/vc-data-model/)
 - [W3C DID] (https://www.w3.org/TR/did-core/)

## Business Requirements

<p> IdngTT Sdn Bhd, a fictional company, wants to develop a digital identity onboarding solution to support unlimited use cases as the underlying identification provider. IdngTT has inaugurated a project called IDDY, which based on Web3.0. IDDY is a mobile application that consists of a Blockchain-based wallet specifically for identity storage. IDDY execute distinct roles in the form of Agent(s). An Agent could be a Holder, Issuer, or Verifier. It performs unique roles based on the designated user type on the platform. </p>

<p> IDDY can integrate through an endpoint to either public or private blockchain ledger to register a credentials definition, log issued credentials public key, also known as the DID, and for verification purposes. For this first phase, IDDY will use Indy Blockchain. <em> Reference to Indy ledger [Indy blockchain](https://indyscan.io/txs/SOVRIN_STAGINGNET/domain) </em> </p> 

<p> A Holder is an entity or a user whose role is strictly to store credentials issued by an institution. E.g. A birth certificate issued by a hospital certified by a Government is a Verifiable Credentials. Similarly, other credential forms are school certificates, employment letters, driver's licences, banking information, or any identification documents. OVerall, these are potential use cases of the verifiable credentials stored on the Blockchain and issued to an end user's(holder) IDDY mobile application. </p>

<p> A Issuer is an entity or an institution that can issue a VC registered on the Blockchain to a holder. IDDY empowers a Holder agent to secure, store, and approve interactions of their credentials with other services through their mobile app. E.g. Issuers can be any of the following: a hospital, university, or an immigration service issuing out credentials to their end users.</p>

<p> A Verifier is an entity, institution or anyone empowered through the IDDY app to verify the authenticity of a VC against the Blockchain. A verifying agent can also be an Issuer in that an issuer must be able to verify the authenticity of their credentials and of others registered on the Blockchain, E.g. An hospital, a university, or an immigration service will be able to prove their issued certificates through IDDY App</p>

### IDDY BA Project Deliverables
<p> As a Business Analyst, create the deliverables for technical and non-technical stakeholders. The main audience is for Software engineers to be able to start implementation. </p>
<p> 
Deliverables for the above case:
</p>

1. Create a Business Requirements Documents (BRD) document for general stakeholders
2. Create a Functional/Technical Specification Document (FSD/TSD) for the engineers or technical stakeholders
3. Create a mock flow diagram to interpret the above.
 ## Points to note
  - This pop quiz will enable us to assess your work quality and documentation for a real project
  - Kindly produce concise/short documents: quality over quantity. You are not required to produce any work that would take beyond the target dates for submission
  - For any queries, reach out to the emails below

# Submission process

1. Email your work to techchallenge@regovtech.com

Good Luck!# web3-developer-pop-quiz
