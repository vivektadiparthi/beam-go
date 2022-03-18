# beam-go

download and Install Go on your machine.

In project directory, create a folder named 'beam-go'

Open git bash with Beam-Go 

go mod init github.com/<yourgithubusername>/beam-go

To check the version of go, use this command:

go version

For getting Apache beam SDK,

go get -u github.com/apache/beam/sdks/v2/go/pkg/beam

To get wordcount program,

go install github.com/apache/beam/sdks/v2/go/examples/wordcount

To run the wordcount program, type in the command

wordcount --input sample.txt --output count

for example, I have used input.txt and my command should be:

wordcount --input input.txt --output counts

The output file will be generated with the name "counts".
