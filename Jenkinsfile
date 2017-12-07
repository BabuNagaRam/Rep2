#!/usr/bin/env groovy
properties([
    [$class: 'GithubProjectProperty',
    displayName: '',
    projectUrlStr: 'https://github.com/BabuNagaRam/Rep2.git/'],
    pipelineTriggers([upstream(
   threshold: 'SUCCESS',
   upstreamProjects: 'https://github.com/BabuNagaRam/Rep1.git/'
   )])])

node
{
stage 'integrate'
echo 'integrated'
stage 'Test'
echo 'Tested'
stage 'Deploy'
echo 'Deployed'
}


