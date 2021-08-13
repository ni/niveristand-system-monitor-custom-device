#!/usr/bin/env groovy
//Leave the above line alone.  It identifies this as a groovy script.
@Library('vs-build-tools') _

//def lvVersions = ['2017', '2018', '2019', '2020']
// This is a map keyed by the bitness of the desired build.
// A build will be run for each version listed for each bitness.
def lvVersions = [
    32: ['2019', '2020', '2021'],
    64: ['2021']]

ni.vsbuild.PipelineExecutor.execute(this, 'vs_cd_build', lvVersions)
diffPipeline(lvVersions[0])
