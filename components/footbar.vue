<template>
        <mdb-footer color="blue" class="font-small pt-4 mt-4">
        <mdb-container class="text-left">
          <mdb-row>
            <mdb-col sm="6">
              <h5 class="title">Contact us</h5>
              <ul>
                <li>Tel: +85620 XX XXX XXX</li>
                <li>Email: horsamoud@gmail.com</li>
                <li>
                  <ul class="list-unstyled list-inline pt-4">
                    <li class="list-inline-item">
                      <b-icon icon="facebook"></b-icon>
                    </li>
                    <li class="list-inline-item">
                      <b-icon icon="chat-fill"></b-icon>
                    </li>
                    <li class="list-inline-item">
                      <b-icon icon="chat-text"></b-icon>
                    </li>
                  </ul>
                </li>
              </ul>
            </mdb-col>
            <mdb-col sm="6">
              <h5 class="title">Support by</h5>
              <ul>
                <li>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                </li>
                <li>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                </li>
                <li>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                </li>
              </ul>
            </mdb-col>
          </mdb-row>
        </mdb-container>
        <hr />
        <div class="footer-copyright text-center py-3">
          <mdb-container fluid>
            &copy; 2020 Copyright: <a href="#"> Horsamod </a>
          </mdb-container>
        </div>
      </mdb-footer>
</template>

<script>
import { mdbFooter, mdbContainer, mdbRow, mdbCol } from 'mdbvue';
export default {
  name: 'FooterPage',
  components: {
    mdbFooter,
    mdbContainer,
    mdbRow,
    mdbCol,
  },
};
</script>

<style>
ul {
  list-style-type: none;
}
</style>
