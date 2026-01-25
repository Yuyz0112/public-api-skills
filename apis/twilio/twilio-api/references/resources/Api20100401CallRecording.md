# Api20100401CallRecording

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/2010-04-01/Accounts/{AccountSid}/Calls/{CallSid}/Recordings.json` | Retrieve a list of recordings belonging to the call used to make the request | [View](../operations/ListCallRecording.md) |
| POST | `/2010-04-01/Accounts/{AccountSid}/Calls/{CallSid}/Recordings.json` | Create a recording for the call | [View](../operations/CreateCallRecording.md) |
| GET | `/2010-04-01/Accounts/{AccountSid}/Calls/{CallSid}/Recordings/{Sid}.json` | Fetch an instance of a recording for a call | [View](../operations/FetchCallRecording.md) |
| POST | `/2010-04-01/Accounts/{AccountSid}/Calls/{CallSid}/Recordings/{Sid}.json` | Changes the status of the recording to paused, stopped, or in-progress. Note: Pass `Twilio.CURRENT` instead of recording sid to reference current active recording. | [View](../operations/UpdateCallRecording.md) |
| DELETE | `/2010-04-01/Accounts/{AccountSid}/Calls/{CallSid}/Recordings/{Sid}.json` | Delete a recording from your account | [View](../operations/DeleteCallRecording.md) |
