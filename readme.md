# Neuroscope
Neuroscope is [Gyroscope](https://github.com/antradar/gyroscope) with an alternative UI model.
It is optimized for document-centric workflows.

## Features

- Fully compitable with the _"classic"_ Gyroscope core
- A more conventional (read: consumer-friendly) user interaction model
- A more compact layout
- Enhanced document authoring facilities
- Additional cross-team communication features

## Transforming the Gyroscope UI
A classic Gyroscope layout uses top icons as Entry Points.
Each icon opens a record list on the left. Entries in the list lead to tabs. The tabs are not synchronized with the left list.
![Gyroscope Layout](https://www.antradar.com/neuro/gyroscope_layout.png)
Neuroscope transforms the layout in several ways.
First, a user who is familiar with consumer web products expects the left panel to be a menu. The disconnected left view and tab content in a classic Gyroscope could be confusing to a conventional user. The ability to quickly launch multiple tabs from the same left list is adventageous in the classic Gyroscope from a navigation point of view. Neuroscope makes a deliverate tradeoff in favor of familiarity.

Another difference in Neuroscope's design is the "attention" it gives to each record. A classic Gyroscope focuses on the relationships between records. One record can quickly pivot to another. This often results in many tabs, and rightfully so. Neuroscope, on the other hand, is optimized for document-centric workflows. Often, there is a notion of a Master Record Type. Instead of opening numerous tabs, Neuroscope consolidates the related records to a long view. The left view panel is therefore utilized to house document bookmarks. Neuroscope as added tab hooks for synchronizing the tab content and the TOC bookmarks.

At the expense of overlapping, and therefore losing dedicated navigation space in the left view, Neuroscope gains more screen realestate. The top icons are moved to the left. A global search makes more sense in a document-oriented Neuroscope than in Gyroscope. Neuroscope also uses more overlays to further save screen space.

![Gyroscope Layout](https://www.antradar.com/neuro/neuroscope_layout.png)

## Porting between Gyroscope and Neuroscope
Both Gyroscope and Neuroscope are version controlled by private repositories. This creates a challenge in version-matching and porting between the two platforms. We make an effort to reconstruct their lineage on GitHub by matching the file dates and commit dates to a specific [Gyroscope version](https://www.antradar.com/download/gyroscope/).

Although the compatible cores of the two systems make the conversion possible, and sometimes even relatively easy, porting between Neuroscope and Gyroscope is a decision that cannot be made lightly. Neuroscope and Gyroscope look at the application (read: your business) differently. A switch in perspective often indicates a drastic change in the business itself.

## Feature Exchange

Selective features are routinely transferred between Gyroscope and Neuroscope. Since Neuroscope applies to a narrower set of domains, certain document-central features stay in Neuroscope. The tranfer from Gyroscope to Neuroscope is also restricted by their different UI models.

## Branding, Versioning and Licensing
Neuroscope is a flavor of Gyroscope. Although it has its own repository and namespace, Neuroscope takes on the same release cadence as the classic Gyroscope. Except for the internal ns_ prefix for Neuroscope-specific components, the use of the gs_ prefix stays. 

>There is also no separate branding for Neuroscope.
>Neuroscope inherits the same branding and licensing terms from Gyroscope.
