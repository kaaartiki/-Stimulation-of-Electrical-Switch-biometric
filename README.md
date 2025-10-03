# -Stimulation-of-Electrical-Switch-biometric  


     #include <stdio.h>
    int main() {
    int fingerprint;
    printf("Fingerprint lock Stimulation\n");
    printf("Enter fingerprint data(0=not matched,1=matched)=");
    scanf("%d",&fingerprint);
    if (fingerprint==1){
        printf("FINGERPRINT MATCHED! Phone Unlocked (ON)\n");
    }
    else{
        printf("FINGERPRINT NOT MATCHED! Phone Locked (OFF)\n");
            }
      
     return 0;
}
