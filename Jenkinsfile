def recentLTS = "2.164.1"
def commonVersion = "2.164.3"
def configurations = [
    [ platform: "linux", jdk: "8", jenkins: null ],
    // windows 
    [ platform: "windows", jdk: "8", jenkins: recentLTS ],
    // java 11 
    [ platform: "linux", jdk: "11", jenkins: recentLTS ],
    // windows
    [ platform: "windows", jdk: "8", jenkins: commonVersion ],
    // java 11
    [ platform: "linux", jdk: "11", jenkins: commonVersion ],
]

buildPlugin(configurations: configurations)