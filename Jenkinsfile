#!/usr/bin/env groovy
//Leave the above line alone.  It identifies this as a groovy script.
@Library('vs-build-tools') _

def lvVersions = [
  32 : ['2019']
]

diffPipeline(lvVersions)
ni.vsbuild.PipelineExecutor.execute(this, 'testing_tools', lvVersions)
