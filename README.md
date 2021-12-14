# Dell EMC ECS-CommunityEdition Fix

This image fixes the problem in emc ecs-communityedition version >= 3.5.0.0 that
`vnest-common-conf.xml` line 547 tag `prop` is unexpected.

To build and tag the image for use, run:
`docker build -f Dockerfile.fix -t emccorp/ecs-software:latest .`
