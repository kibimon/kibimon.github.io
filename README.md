#  About MonStrPub

<dfn>Mon</dfn> (a clipping of <i>monsters</i>) are collectible virtual entities, which typically come in a number of varieties and feature unique traits or personalities.
<dfn>MonStrPub</dfn> is an [extension](https://www.w3.org/TR/activitystreams-core/#extensibility "ActivityStreams 2.0 § 5. Extensibility") to [ActivityPub] for supporting mon in a federated context.

##  Quick Links {#fastlinks}

Specifications
: [MonStrPub]
: [RPPub]

Implementations
: [Coverage list](./coverage/)
: [Monstodon]
: [Plé-Mon]

About
: [KibiMon](./kibimon/)
: [Contributing](./contributing/)

##  The Specifications  {#specs}

[MonStrPub] is defined through a large number of specifications.
All MonStrPub implementations *must* support [MonStrPub Core], which lays down basic ground-rules for transmitting mon information.
In addition to this, implementations *may* support any of a large number of *optional* specifications, which add functionality on top of this system.

This design approach was chosen to help create a clear path towards implementation and to ensure interoperability between servers which implement some, but not all, of MonStrPub's vast set of features.
It also makes it easier for third parties to define their *own* MonStrPub extensions without breaking compatibility with other servers.

MonStrPub is itself built upon another set of specifications, known as [RPPub].
RPPub provides an abstract vocabulary for use in roleplaying contexts and puts forth a set of basic requirements for handling these objects.
The RPPub specification may later be used as the foundation for any manner of specifications, not just ones involving mon.

You can view an overview of the specifications which make up MonStrPub [here][MonStrPub], or which make up RPPub [here][RPPub].

##  The Software  {#software}

Naturally, having specifications is meaningless if there aren't any platforms which support them.
For this reason, the KibiMon team is working hard to develop supporting MonStrPub implementations alongside the current specs.
(And others may join in the effort as well!)

You can view the current list of known implementations, alongside information about which specifications are covered, [here](./coverage/).

##  Who Did This?  {#who}

MonStrPub is developed by [KibiMon].
You can learn more about them [here](./kibimon/).

##  Getting Involved  {#contribute}

Want to contribute to MonStrPub?
Find more information [here](./contributing/).


[ActivityPub]:    <https://www.w3.org/TR/activitypub/>              "ActivityPub"
[KibiMon]:        <https://github.com/kibimon/>                     "KibiMon &#124; GitHub"
[MonStrPub]:      <https://www.monstr.pub/spec/monstrpub-overview/> "MonStrPub"
[MonStrPub Core]: <https://www.monstr.pub/spec/monstrpub-core/>     "MonStrPub Core"
[Monstodon]:      <https://www.monstr.pub/monsto/>                  "Monstodon"
[Plé-Mon]:        <https://www.monstr.pub/ple/>                     "Plé-Mon"
[RPPub]:          <https://www.monstr.pub/spec/rppub-overview/>     "RPPub"
