Di View tambahkan button nah nanti panggil class BukuPDF dengan constructor 

Example
private void btnreportActionPerformed(java.awt.event.ActionEvent evt) {                                          
        try {
            // TODO add your handling code here:
            BukuPDF books = new BukuPDF();
            books.PDF(); //panggil ke method PDF 
        } catch (Exception ex) {
            Logger.getLogger(FormBuku.class.getName()).log(Level.SEVERE, null, ex);
        }finally{
            JOptionPane.showMessageDialog(null,"Berhasil dicetak");
        }
    }         
