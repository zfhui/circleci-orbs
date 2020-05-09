# A Collection of CircleCI Orbs

* `zfhui/ruby-gem`

## Steps for authoring an Orb:

* create your Orb: `touch ruby-gem.yml`
* validate Orb: `circleci orb validate ruby-gem.yml`

## Steps for publish an Orb:

To *dev*:

* `circleci orb publish ruby-gem.yml zfhui/ruby-gem@dev:first`

To *public*:

```
  circleci orb create zfhui/ruby-gem # when publishing for the first time
  circleci orb publish ruby-gem.yml zfhui/ruby-gem@0.1.0 # replace the version after `@` with your own
```

## Sources:

[Orb Authoring Process](https://circleci.com/docs/2.0/orb-author/#writing-inline-orbs)
