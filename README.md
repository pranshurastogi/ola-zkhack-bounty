# ola-zkhack-bounty

<img width="1440" alt="Screenshot 2023-11-11 at 7 51 24 AM" src="https://github.com/pranshurastogi/ola-zkhack-bounty/assets/12568291/c49708e6-e73e-42fe-8040-426dcb3d7f39">


## Correction :

* Changed the initialization of voteCount to 0
* Added a condition to check if sender.voted is false
*  Added proposals[proposal_].voteCount += 1; to increment the vote count of the voted proposal.
* Included the line winningProposal_ = p; within the if-statement to assign the index of the proposal with the highest vote count to winningProposal_
* Added u32 winnerName = proposals[winnerP].name; to retrieve the name of the winning proposal based on the index returned from winningProposal()
