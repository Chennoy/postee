# Postee Route Configuration

You could use Postee with any json. See the following example receiving json events:

### Route Tracee Message

The following input JSON message is from [Tracee](https://github.com/aquasecurity/tracee).

Set `input` property of route to: `contains(input.SigMetadata.ID,"TRC-")` to limit the route to handle Tracee messages only

In the section [rego-templates](https://github.com/aquasecurity/postee/tree/main/rego-templates) have rego templates samples to use with Tracee:
- tracee-html.rego
- tracee-slack.rego