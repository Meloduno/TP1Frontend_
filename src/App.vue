<template>
<v-app>
  <v-container>
      <v-row>
        <v-col sm="12" md="6">
          <v-card class="">
            <v-img src="logo.jpg" max-height="48" contain></v-img>
          </v-card>
        </v-col>
        <v-col sm="12" md="6">
          <v-card class="d-flex justify-center">
          <v-card-actions>
          <v-btn>
            home
          </v-btn>

          <v-btn>
            productos
          </v-btn>

          <v-btn>
            nosotros
          </v-btn>

          <v-btn>
            contacto
          </v-btn>
        </v-card-actions>
        </v-card>
        </v-col>
      </v-row>  
  </v-container>
  
  <v-container>
  
    <v-row  justify="center">
      <v-col cols="12">
        <v-card>  
  
            <v-img 
            
            src="https://nikearprod.vtexassets.com/assets/vtex.file-manager-graphql/images/c0aff875-3610-4a2c-9f0d-3e527223256e___91e0619c56f642436e2f5227d1ef7a46.png">
             <v-containter>
              <v-row justify="center" >
                <v-col cols=4>
                  <h1>WINTER SALE 50%OFF</h1>
                </v-col>
              </v-row>
            </v-containter> 
          </v-img>
        
          </v-card>
      
        </v-col>
    
      </v-row>
  
    </v-container>

    <v-divider color="#FFFFFF"></v-divider>
    
<v-container>
  <v-row justify="center">
    <v-col cols="10" class="text-center">
          <h1>PRODUCTOS DESTACADOS</h1>
      <v-carousel 
        cycle 
        show-arrows="hover"
        hide-delimiters>

        <v-carousel-item>
          <v-img 
            src="https://sportline.vtexassets.com/assets/vtex.file-manager-graphql/images/7ad63453-0f1e-49f6-9e15-cde2dd9d2f17___50a08f17bf3b7c6b9cc658871c8db111.webp" height="500" contain>
          </v-img>
        </v-carousel-item>

        <v-carousel-item>
          <v-img 
            src="https://sportline.vtexassets.com/assets/vtex.file-manager-graphql/images/ef4ddbab-a53d-498e-aa1a-4220a5feb19b___3eff14fa6f921cf7dc17b701ef791815.webp" height="500" contain>
          </v-img>
        </v-carousel-item>

        <v-carousel-item>
          <v-img 
            src="https://sportline.vtexassets.com/assets/vtex.file-manager-graphql/images/3e350840-a8c5-45d4-bc08-2e2d71608983___6e8dca2ed94eabfc0bb4cb463f57795c.webp" height="500" contain>
          </v-img>
        </v-carousel-item>

      </v-carousel>
    </v-col>
  </v-row>
</v-container>

<v-divider color="#FFFFFF"></v-divider>

    <v-container>
      
      <v-row justify="center">   
        <v-col cols="12" class="text-center">
          <h1>PRODUCTOS NUEVOS</h1>
          </v-col>             

        <v-col xs="12" sm="6">

          <v-card>

          <v-img 
          src="https://nikearprod.vtexassets.com/assets/vtex.file-manager-graphql/images/3b436a22-00c1-4f6d-9093-813074229752___bb491c506fd41ebc3a04de21300411c5.png">
          </v-img>
          
          <v-card-title>
            Air Force
          </v-card-title>

          <v-card-text>
            $123456
          </v-card-text>

          <v-card-actions>
            <v-btn color="info">Comprar</v-btn>
          </v-card-actions>

        </v-card>
      </v-col>

      <v-col xs="12" sm="6">
        <v-card>

          <v-img src="https://nikearprod.vtexassets.com/assets/vtex.file-manager-graphql/images/ab40d5f6-f3cf-46cb-93bc-0a2d33d8450e___6e62025c8381dab7a40c7506d5568611.png">

          </v-img>
          
          <v-card-title>
            Dunk
          </v-card-title>

          <v-card-text>
            $123456
          </v-card-text>

          <v-card-actions>
            <v-btn color="info">Comprar</v-btn>
          </v-card-actions>

        </v-card>
      </v-col>
    </v-row>
  </v-container>
  <v-divider color="#FFFFFF"></v-divider>
  <v-cointainer>
    <v-row justify="center">
      <v-col cols="10">
        <v-row>
          <v-col cols="12" class="text-center">
            <h1>CATEGORIAS</h1>
          </v-col>  
          <v-col xs="12" sm="4">
            <v-card>
            
              <v-img 
                src="https://nikearprod.vtexassets.com/assets/vtex.file-manager-graphql/images/29834e1c-5ade-4441-a6ca-fb044544d551___2a3a03769ab2ef7cd04156a5da55ec52.png"
                height="500">
              </v-img>

              <v-card-title>  
                <h3>Mujer</h3>
              </v-card-title>   
  
              <v-card-actions>
              <v-btn color="info" flat>Catalogo</v-btn>
              </v-card-actions>
                  
            </v-card>  
          </v-col>
      
          <v-col xs="12" sm="4">    
            <v-card>
            
              <v-img 
                src="https://nikearprod.vtexassets.com/assets/vtex.file-manager-graphql/images/97e25ecf-53f7-4175-a62d-f5ba129b6b84___402a44773a86cef32ff542af39bfa32e.png"
                height="500">
              </v-img>

              <v-card-title>
                <h3>Hombre</h3>
              </v-card-title>   

              <v-card-actions>
 
                <v-btn color="info" flat>Catalogo</v-btn>
 
              </v-card-actions>

            </v-card>
 
          </v-col>

         <v-col xs="12" sm="4">
 
          <v-card>
            
              <v-img 
                src="https://nikearprod.vtexassets.com/assets/vtex.file-manager-graphql/images/2b097152-18aa-4c3c-b899-cb06f82d041e___d9c64b871e4bba5f36f5eb76eacad491.png" 
                height="500">
 
              </v-img>

              <v-card-title>
 
                <h3>Niño/a</h3>
 
              </v-card-title>   

              <v-card-actions>
 
                <v-btn color="info" flat>Catalogo</v-btn>
 
              </v-card-actions>

            </v-card>
 
          </v-col>
 
        </v-row>
 
      </v-col>
 
    </v-row>
 
  </v-cointainer>
 
  <br>
 
  <v-footer color="#888888">

    <v-container>

      <v-row justify="center">

        <v-col xs="10" sm="8" md="6" lg="4" xl="3">

          <v-card class="d-flex justify-center">

            <v-card-actions>

              <template>

                <div class="text-center">
    <v-btn
      @click="dialog = true"
    >
      Redes sociales
    </v-btn>

    <v-dialog
      v-model="dialog"
      width="auto">
      
      <v-card>

        <v-card-text>

          <h2><br>

            <a href="#">Facebook</a><v-icon>mdi-facebook</v-icon><br>

          <a href="#">Twitter</a><v-icon>mdi-twitter</v-icon><br>
        
        <a href="#">Instragram</a><v-icon>mdi-instagram</v-icon><br>

      </h2>  

    </v-card-text>

    <v-card-actions>

      <v-btn color="#333333" block @click="dialog = false">Cerrar</v-btn>

    </v-card-actions>

  </v-card>

</v-dialog>

</div>

</template>

              <v-btn>
                Contacto
              </v-btn>

            </v-card-actions>

          </v-card>

        </v-col>

      </v-row>

    </v-container>

  </v-footer>

</v-app>

</template>

<script>
  export default {
    data () {
      return {
        dialog: false,
      }
    },
  }

</script>
