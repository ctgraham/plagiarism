For this plugin to work, the following must be added to your config.inc.php file:

;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;
; iThenticate Plugin Settings ;
;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;

[ithenticate]

; Enable iThenticate to submit manuscripts after submit step 4
ithenticate = On

; Credentials can be set by context : specify journal path
; The username to access the API (usually an email address)
;username[MyJournal_path] = "user@email.com"
; The password to access the API
;password[MyJournal_path] = "password"

; default credentials
; The username to access the API (usually an email address)
username = "user@email.com"

; The password to access the API
password = "password"
