---
layout: page
title: projects
permalink: /projects/
nav: true
nav_order: 1
horizontal: true
---


<div class="row justify-content-sm-center mt-5">
    <div class="col-md-6 mt-3 mt-md-0">
      <h2 class="post-title"> Data-driven low dimensional manifolds </h2>
      <p> Reacting flow simulations are computationally costly due to the large number of chemical species involved, whose coupled evolutions require solving for as many differential equations as there are chemical species. The goal of this project is to use machine learning techniques to create a low-dimensional, data-driven representation of the chemical state and evolve this low-dimensional representation forward in time both stably and accurately for predictive capabilities. </p>
    </div>
    <div class="col-md-6 mt-3 mt-md-0">
      <div class="text-center">
            <img class="img-fluid rounded z-depth-1" src="/assets/img/model6.png" width="100%" height="auto" >
            <figcaption class="caption">Schematic depicting an autoencoder for generating a low-dimensional manifold of the chemical state</figcaption>
          </div>
    </div>
</div>



<div class="row justify-content-sm-center mt-5">
    <div class="col-md-6 mt-3 mt-md-0">
      <div class="text-center">
            <img class="img-fluid rounded z-depth-1" src="/assets/img/pac.jpeg" width="80%" height="auto" >
            <figcaption class="caption">Temperature profiles for plasma-assisted ignition cases comparing the detailed chemical mechanism (solid lines) and the reduced skeletal mechanism (markers)</figcaption>
      </div>
    </div>
    <div class="col-md-6 mt-3 mt-md-0">
      <h2 class="post-title"> Chemical kinetic mechanism reduction </h2>
      <p> Generating skeletal kinetic mechanisms by removing unimportant species and reactions is critical for making reacting flow simulations computationally traceable. One of my first Ph.D. projects was extending a graph-based kinetic reduction methodology to a new plasma-assisted combustion (PAC) application.  </p>
      <p> More recently, in collaboration with the National Renewable Energy Lab, I've worked on reducing sustainable aviation fuel (SAF) kinetic mechanisms to aid in the development of next generation aircraft engine technologies. </p>
    </div>

</div>




<div class="row justify-content-sm-center mt-5">
    <div class="col-md-6 mt-3 mt-md-0">
      <h2 class="post-title"> LES-PDF turbulent combustion modeling </h2>
      <p>The LES-PDF modeling framework is a method for modeling chemistry within a large eddy simulation (LES).  In the LES-PDF framework, notional particles are used to represent the chemical state, which are convected by the flow and evolve via a mixing model to approximate diffusive processes, and reactions, which are directly computed from the kinetic mechanism.</p>
      <p> The LES-PDF simulations are the end goal test for our low-dimensional manifolds and I recently implemented the LES-PDF framework into our new CFD solver called NGA2. </p>
    </div>
    <div class="col-md-6 mt-3 mt-md-0">
            <img class="img-fluid rounded z-depth-1" src="/assets/img/part_flame.gif" width="auto" height="auto" >
            <figcaption class="caption">A lifted n-dodecane flame simulation using our group's CFD solver NGA2 showing (top) the Euleurian mesh and (bottom) notional particles representing the chemical state both colored by temperature </figcaption>
    </div>
</div>

<!-- Since the chemical length scales are often no longer resolved on an LES mesh, (imagine a flame with a thin reaction zone with unburnt reactants and hot products on either side, all contained within a single cell on the Eulerian mesh), the average temperature and species concentrations of the cell would lead to erroneous rate calculations. -->
<!-- <div class="row justify-content-sm-center mt-5">
    <div class="col-md-6 mt-3 mt-md-0">
            <img class="img-fluid rounded z-depth-1" src="/assets/img/pac.jpeg" width="auto" height="auto" >
            <figcaption class="caption">caption caption caption</figcaption>
    </div>
    <div class="col-md-6 mt-3 mt-md-0">
      <h2 class="post-title"> Plasma-assisted combustion </h2>
      <p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. Aenean ultricies mi vitae est. Mauris placerat eleifend leo.</p>
    </div>
</div> -->
