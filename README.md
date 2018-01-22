# CBAS Resources

This is an umbrella repository for the data we generate on ***Lendenfeldia chondrodes***. It contain pointers to other repositories with data on this system.

Note that these other repositories are mantained independently and that this repository uses the **submodule** capability of git to pull those repositories and the most recent changes pushed to them. This repository **should not be used to introduce changes to the submodules**, it was only created to centralize all the data generated on this system. If you want to contribute to one of the repositories you will have send a pull request to that repository. Maybe this is too complicated but the way in which the project develops makes it easier to develop independent repositories and only add the submodule to this repository once the specific experiments are concluded.

The goal of this repository is to provide users with one single repository that can be cloned and from which all information generated on *L. chondrodes* can be easily fetched and kept together.

I hope this makes sense, and it makes your lives easier.

cheers

Sergio


# Cloning instructions

Copy the url using the clone button on the main page of this repository and open a terminal. If you want git to fetch and update all the submodules on cloning you need to pass the *--recursive* flag to *git clone*. Otherwise you need to use the *git submodule init* followed by *git submodule update*. This combination will fetch the data from the submodule repositories.


# About *L. chondrodes* and the experimental settings used for different experiments

Details about the aquarium setting used to keep *L. chondrodes* and some details about the experimental settings used for different projects can be found in the Wiki.
