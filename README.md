# Bitcoin-Adress-Generator
Generate Bitcoin private key and Bitcoin address



##### ------------------------------ DEUTSCH ------------------------------

Der Bitcoin Adress Generator erstellt einen privat Schlüssel im Bitcoin Wallet Import Format WIF,           
sowie die zugehörige Bitcoin-Adresse und den öffentlichen Schlüssel.            
Eine grafische Benutzeroberfläche "GUI" wurde implementiert.                         
Es kann eine Paper-Wallet mit QR-Code erstellt und ausgedruckt werden.  
    
Dies ist eine Java Anwendung, sie müssen also Java installieren!



#### Multilanguage 
Derzeit sind 5 Sprachen implementiert:
Englisch, Deutsch,  Französisch, Russisch, Chinesisch.      
Erweiterung von weiteren Sprachen sind leicht möglich.



#### Eingabe:
Zum Erstellen des Private Key´s gibt es drei Möglichkeiten:

1. Eingabe als Text:                                    
Es kann ein beliebiger Text eingegeben werden. 
Aus diesem Text wird dann durch einen Hash der Private Key,                 
Public Key und die Bitcoin Adresse erzeugt.

2. Würfelzeichen:                                   
Es können 100 Würfelzeichen in Base6 (also Zeichen zwischen 1 und 6) eingegeben werden.

3. Der Private Key kann aber auch direkt in allen üblichen Formaten eingegeben werden:
Hexa, Base58, Base58 compressed und Base64.
Checksumme Prüfung ist implementiert.



#### Ausgabe
- Die Ausgabe des Private Key´s erfolgt in allen üblichen Formaten: Hexa, Base58, Base58 compressed, Base64
- der öffentliche Schlüssel wird in Hexa ausgegeben. (X und Y Koordinate)
- Die Bitcoin Adresse wird in Base58 ausgegeben
- Der QR-Code der Bitcoin Adresse wird angezeigt



#### QR-Code Prüfung
Zur Sicherheit wird der QR-Code vom Programm selbst als Bild wieder eingelesen, 
gescannt und geprüft.                       
Damit wird verhindert, dass ein falscher QR-Code angezeigt werden könnte.



#### Paper Wallet erstellen.
Die Oberfläche des Programms kann als Bild ausgedruckt oder gespeichert werden. 
Es gibt auch die Möglichkeit den Private-Key zu verdecken. 
Aber Achtung! Wird der Private Key verdeckt und das Bild ausgedruckt oder gespeichert, 
kann daraus später der Private Key nie wieder herstellt werden. 
Sie müssen den Private Key in dem Fall dann gesondert speichern.
Wenn sie nicht sicher sind, verdecken sie den Private Key lieber nicht!



#### Dieses Programm ist keine Desktop Wallet!
Das Speichern der Wallet mit samt Private Key ist aus Sicherheitsgründen nicht vorgesehen.
Sie können nur die Oberfläche mit allen Key´s als Bild abspeichern oder ausdrucken.
Wenn sie das Programm schließen, ohne vorher das Bild ausgedruckt oder gespeichert zu haben, 
sind alle eingegebenen Key´s unwiderruflich verloren!

Unter der Registerkarte „Stil“ können sie alle möglichen Farbeinstellungen vornehmen.
Alle Einstellungen des Programms, wie Sprachen, Stil, etc. werden in der Datei: BAGen.cfg gespeichert.



#### Spenden
Wenn Ihnen der Bitcoin Adress Generator gefällt, würde ich mich über eine Spende sehr freuen: 
#### 12zeCvN7zbAi3JDQhC8tU3DBm35kDEUNiB 
   




#### Haftungsausschluss

DIESE SOFTWARE WIRD VON DEN COPYRIGHT-INHABERN UND -BETREIBERN "WIE GESEHEN" ZUR VERFÜGUNG GESTELLT. 
JEGLICHE AUSDRÜCKLICHE ODER IMPLIZITE GEWÄHRLEISTUNG, EINSCHLIESSLICH, 
ABER NICHT BESCHRÄNKT AUF DIE STILLSCHWEIGENDEN GEWÄHRLEISTUNGEN DER MARKTGÄNGIGKEIT 
UND DER EIGNUNG FÜR EINEN BESTIMMTEN ZWECK, WIRD ABGELEHNT. 
IN KEINEM FALL HAFTEN DER COPYRIGHT-INHABER ODER DIE BEITRÄGER FÜR DIREKTE, 
INDIREKTE, ZUFÄLLIGE, SPEZIELLE, EXEMPLARISCHE ODER FOLGESCHÄDEN (EINSCHLIESSLICH, 
ABER NICHT BESCHRÄNKT AUF, BESCHAFFUNG VON ERSATZGÜTERN ODER DIENSTLEISTUNGEN; 
VERLUST VON VERWENDUNG, DATEN ODER GEWINNEN; ODER GESCHÄFTSUNTERBRECHUNG) JEDOCH AUFGRUND DER HAFTUNGSFREISTELLUNG, 
AUCH IM VERTRAG, AUSSCHLIESSLICHER HAFTUNG ODER TATSACHE (EINSCHLIESSLICH FAHRLÄSSIGKEIT ODER ANDERWEITIG), 
DIE SICH AUS DER NUTZUNG DIESER SOFTWARE ERGEBEN, SELBST WENN SIE AUF DIE MÖGLICHKEIT SOLCHER SCHÄDEN BERATEN WIRD.









#### Disclaimer
THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE
LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
POSSIBILITY OF SUCH DAMAGE.




