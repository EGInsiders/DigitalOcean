# Create a new Step
Given that I am on the "Goal Steps" Page
And that I am creating a new team goal

###

# Starting a new step

When I click "Add Step"
Then a create new step form appears

###

#Configuring the new step

Given that I have clicked "Add Step"
Then I enter in a step name
And step notes
And a Start Date
And a Due Date
And set the Reminder as "1 Day Before"
And attach a resource
And click "done"
Then the step is saved
and the step is displayed on the new step page

###
