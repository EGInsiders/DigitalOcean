# Set Goal Settings

Given that I am viewing the Goal Settings Page
When I change the status of "active" to "draft"
Then I am taken to the "Update Team Member Goals"
And Not yet adopted the goal is checked
And not yet completed the goal is checked
And completed the goal (if you've added steps, your changes will make their goal incomplete)
And override user edits is unchecked
and click "confirm changes"
Then I am taken to the Goal Detail Page
