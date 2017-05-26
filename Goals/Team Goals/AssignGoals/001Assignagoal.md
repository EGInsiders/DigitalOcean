# Initiate Assign Goal

When I click on the command menu
And click on "Assign Goal to Members"
Then I am taken to the "Assign Goal" page

###

# Select Members to assign the goal to

When I click on "Add Members"
Then the Select Members modal appears

###

# Select Members from Modal

When I click on "Assign to Goal" next to a target member
Then the member becomes selected
And "Assign to Goal" disappears

###

# Closing Select Members Modal

When I click on the "X"
Then the modal disappears

###

# Submit assigned goal to members

Given that I've selected member(s) from the team
and entered a custom message
And click "Assign Goal"
Then I am taken back to the goal detail page
And the assigned member(s) are shown in the list of adoptees

###
