# CoreDataEvenTimes

## Lab
1. We’re going to make one small change to this project. 
1. The person asking you to make this app really likes even numbers.
1. So they want a checkmark on timestamps that have an even number of minutes and seconds in the timestamp.
1. Lets make the changes together

###  Core Data Model
1. Right now the `Item` entity only has one property: `timestamp: Date`
1. Lets add a new property: `hasEvenMinutesAndSeconds: Boolean`

### Update the Item
1. Lets add a new function to determine if a particular Date has an even number in both the minutes and seconds
1. Add it right after the `addItem()` func

1. Now we have to make sure this new property is correct when we create a new `Item`
1. Lets figure out if the Item has an even number of minutes and seconds and save it to the `Item`
1. Make your addItem() look like this:

### Update the UI
1. Finally -> Update your UI to show the checkmark for Item’s who’s `hasEvenMinutesAndSeconds` is true
1. Make your NavigationLink look like this:


1. Does it look like this?!

## Done!

### Time left?
- If you have any remaining time:
    - Try to add something else to the `Item` entity
    - Read from the docs (here)[https://developer.apple.com/documentation/coredata]
    - Start reading the docs for tomorrow's lesson (here)[https://developer.apple.com/documentation/coredata/modeling_data]
