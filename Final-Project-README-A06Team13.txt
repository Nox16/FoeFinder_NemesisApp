FoeFinder Nemesis "Dating" App

Team Members:
Matthew Hammans
Sasha Velet
Matthew Clark

XCode 14.2

**Use Tutorial**
The FoeFinder App is an application meant to feel similar to a dating app but is intended to
help users find their nemesis. After creating an account and logging in the user can use the
matching screen to selected matches for a potential nemesis. This is done by pressing the
right facing arrow to match, or left facing arrow to not-match. After selecting matches, the
user can go to the match history screen to view a table of their match history, including 
the names and photos of other people they've matched with. Lastly, the user can go to the
mapped matches screen to view a real time map of users around them, to give them a sense of
their potential nemsis's movements.

**Team Responsibilities**

Matthew Clark (matkclar):
1) View Construction / Storyboard Assembly
2) Profile Generator
2) xcassets Stock Image Storage and Use
4) SpriteKit Animations for Matching Screen
5) Matching Screen Labels & Images

Sasha Velet (svelet):
1) Messaging Skeleton Code
2) Match History Skeleton Code
3) Profile Editing Skeleton Code
1) Mapping "Matches"
2) Notifications

Matthew Hammans (mmhamman):
1) Log-In
2) Persistent Storage
3) Matching Arrays
4) Match History Cell Construction

**Xcode Project Environment**
- Xcode Version 14.2
- Henna Repo
- "a06" Folder
- Does not required hardware for testing
- Test on IPhone Simulator / Hardward

**Features & Implementation (Feature : File Name (.swift))**
- Matching  : MatchViewController
- Match History : MatchHistoryViewController & MatchCellTableViewCell
- Mapped Matches : MappedViewController
- Editing Profile : EditProfileViewController

**Changes**
We removed the Messaging functionality and view entirely. Due to feedback from the Instruction staff,
we realized because the scope of our App's Demo was limited to no server access or wifi connection
it would be easier to remove the plans for that functionality. It was removed in between the
Alpha and Beta (A04 --> A05). The code was barely changed, except the still existing
"MessasingViewController" is now not connected to or implemented anywhere.

