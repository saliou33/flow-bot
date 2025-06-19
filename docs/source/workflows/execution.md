# Workflows Execution

An execution is the process of running a workflow triggered by an event. For example, a trigger message from a WhatsApp user (text or media) initiates the entire workflow. The execution can succeed, fail, or produce an error message, which is available for debugging. The platform allows real-time tracking of executions. Each execution has its own context, where variables are evaluated (e.g., `${{context.sender}}` for the sender’s phone number).
