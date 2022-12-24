# Generate a random GUID with the structure 8-4-4-4-12
function Get-RandomGUID {
    # Define the structure of the GUID as an array of hexadecimal lengths
    $hexLengths = @(8, 4, 4, 4, 12)

    # Create an empty string to store the random GUID
    $randomGUIDString = ""

    # Generate a random hexadecimal string for each segment of the GUID structure
    foreach ($hexLength in $hexLengths) {
        # Generate a random hexadecimal string of the specified length
        $randomHexString = (1..$hexLength | %{ '{0:X}' -f (Get-Random -Max 16) }) -join ''

        # Add the segment to the random GUID string, separated by a dash
        $randomGUIDString += "$randomHexString-"
    }

    # Remove the last dash from the random GUID string
    $randomGUIDString = $randomGUIDString.Substring(0, $randomGUIDString.Length-1)

    # Ensure the generated GUID doesn't match Microsoft's default GPO GUIDs
    if ($randomGUIDString -eq "31B2F340-016D-11D2-945F-00C04FB984F9" -or $randomGUIDString -eq "6AC1786C-016F-11D2-945F-00C04FB984F9") {
        # If the generated GUID matches a default GPO GUID, generate a new GUID and return it
        Get-RandomGUID
    } else {
        # Otherwise, return the generated GUID
        return $randomGUIDString
    }
}

# Generate a random GUID and store it in the $RandomGUID variable
$RandomGUID = Get-RandomGUID

# Print the generated GUID to the screen
Write-Output $RandomGUID
