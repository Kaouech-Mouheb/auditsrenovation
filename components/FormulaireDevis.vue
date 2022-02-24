<template>
  <div>
    <v-card>
      <v-card-title class="text-primary"> Devis Gratuit </v-card-title>
      <v-card-text>
        <v-row>
          <v-col cols="12" md="8">
            Remplissez ce formulaire pour recevoir votre devis gratuit et sans
            engagement sous 24h ouvrés.
          </v-col>
          <v-col cols="12" md="4">
            <img src="rge.jpeg" width="70px" />
          </v-col>
        </v-row>
      </v-card-text>

      <v-card-text>
        <v-form>
          <v-select
            :items="[
              'Isolation des combles',
              'Aménagement de combles',
              'Traitement Bois Charpente',

              'isolation thermique',
              'travaux de couverture',
              'travaux de peinture',
              'Isolation des murs par l\'intérieur',
              'Isolation des murs par l\'extérieur',
              'Ravalement de façade',
              'Traitement de façade',
              'Isolation toiture par l\’extérieur',
              'Isolation sous toiture',
              'Rénovation de toiture',
              'Démoussage toiture',
              'Traitement de toiture',
              'Menuiseries, fenêtres, portes',
              'Ventilation, VMC',
              'Isolation garage',
              'Autres',
            ]"
            label="Type de travaux"
            required
          ></v-select>

          <v-text-field label="Nom *" single-line></v-text-field>
          <v-text-field label="code postal *" single-line></v-text-field>
          <v-text-field label="votre téléphone *" single-line></v-text-field>
          <v-text-field label="votre email *" single-line></v-text-field>
          <v-textarea
            clearable
            clear-icon="mdi-close-circle"
            label="Décrivez votre projet et leur de rappel souhaitée"
          ></v-textarea>
          <v-btn color="primary">Envoyer ma demande de devis</v-btn>
          <small class="d-block mt-4">
            Vos données personnelles sont collectées exclusivement dans le cadre
            de votre demande de devis et ne font l’objet d’aucune diffusion ni
            commercialisation. Elles sont destinées au personnel de Mieux
            Rénover en charge du traitement de votre demande. Le présent site
            est déclaré à la CNIL sous le n° 1502515v0.
          </small>
        </v-form>
      </v-card-text>
    </v-card>
  </div>
</template>
