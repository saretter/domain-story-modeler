#!/usr/bin/env groovy
@Library('sbs-jenkinslib@stable')_

/*
 * T-Systems SBS pipeline build see below link for documentation details.
 * https://sbs.t-systems.com/wiki/Job+Type%3A+Jenkins+Pipeline+Build
 */
sbsBuild(
    pipeline: this,
    buildContainerImage: "node:10",
    buildStep: [
        scriptName: './build.sh',
    ]
);
