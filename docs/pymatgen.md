---
layout: default
title: API Documentation
nav_order: 6
---

# pymatgen namespace

## Subpackages


* [pymatgen.alchemy package](pymatgen.alchemy.md)




    * [pymatgen.alchemy.filters module](pymatgen.alchemy.md#module-pymatgen.alchemy.filters)


        * [`AbstractStructureFilter`](pymatgen.alchemy.md#pymatgen.alchemy.filters.AbstractStructureFilter)


            * [`AbstractStructureFilter._abc_impl`](pymatgen.alchemy.md#pymatgen.alchemy.filters.AbstractStructureFilter._abc_impl)


            * [`AbstractStructureFilter.test()`](pymatgen.alchemy.md#pymatgen.alchemy.filters.AbstractStructureFilter.test)


        * [`ChargeBalanceFilter`](pymatgen.alchemy.md#pymatgen.alchemy.filters.ChargeBalanceFilter)


            * [`ChargeBalanceFilter._abc_impl`](pymatgen.alchemy.md#pymatgen.alchemy.filters.ChargeBalanceFilter._abc_impl)


            * [`ChargeBalanceFilter.test()`](pymatgen.alchemy.md#pymatgen.alchemy.filters.ChargeBalanceFilter.test)


        * [`ContainsSpecieFilter`](pymatgen.alchemy.md#pymatgen.alchemy.filters.ContainsSpecieFilter)


            * [`ContainsSpecieFilter._abc_impl`](pymatgen.alchemy.md#pymatgen.alchemy.filters.ContainsSpecieFilter._abc_impl)


            * [`ContainsSpecieFilter.as_dict()`](pymatgen.alchemy.md#pymatgen.alchemy.filters.ContainsSpecieFilter.as_dict)


            * [`ContainsSpecieFilter.from_dict()`](pymatgen.alchemy.md#pymatgen.alchemy.filters.ContainsSpecieFilter.from_dict)


            * [`ContainsSpecieFilter.test()`](pymatgen.alchemy.md#pymatgen.alchemy.filters.ContainsSpecieFilter.test)


        * [`RemoveDuplicatesFilter`](pymatgen.alchemy.md#pymatgen.alchemy.filters.RemoveDuplicatesFilter)


            * [`RemoveDuplicatesFilter._abc_impl`](pymatgen.alchemy.md#pymatgen.alchemy.filters.RemoveDuplicatesFilter._abc_impl)


            * [`RemoveDuplicatesFilter.test()`](pymatgen.alchemy.md#pymatgen.alchemy.filters.RemoveDuplicatesFilter.test)


        * [`RemoveExistingFilter`](pymatgen.alchemy.md#pymatgen.alchemy.filters.RemoveExistingFilter)


            * [`RemoveExistingFilter._abc_impl`](pymatgen.alchemy.md#pymatgen.alchemy.filters.RemoveExistingFilter._abc_impl)


            * [`RemoveExistingFilter.as_dict()`](pymatgen.alchemy.md#pymatgen.alchemy.filters.RemoveExistingFilter.as_dict)


            * [`RemoveExistingFilter.test()`](pymatgen.alchemy.md#pymatgen.alchemy.filters.RemoveExistingFilter.test)


        * [`SpecieProximityFilter`](pymatgen.alchemy.md#pymatgen.alchemy.filters.SpecieProximityFilter)


            * [`SpecieProximityFilter._abc_impl`](pymatgen.alchemy.md#pymatgen.alchemy.filters.SpecieProximityFilter._abc_impl)


            * [`SpecieProximityFilter.as_dict()`](pymatgen.alchemy.md#pymatgen.alchemy.filters.SpecieProximityFilter.as_dict)


            * [`SpecieProximityFilter.from_dict()`](pymatgen.alchemy.md#pymatgen.alchemy.filters.SpecieProximityFilter.from_dict)


            * [`SpecieProximityFilter.test()`](pymatgen.alchemy.md#pymatgen.alchemy.filters.SpecieProximityFilter.test)


        * [`SpeciesMaxDistFilter`](pymatgen.alchemy.md#pymatgen.alchemy.filters.SpeciesMaxDistFilter)


            * [`SpeciesMaxDistFilter._abc_impl`](pymatgen.alchemy.md#pymatgen.alchemy.filters.SpeciesMaxDistFilter._abc_impl)


            * [`SpeciesMaxDistFilter.test()`](pymatgen.alchemy.md#pymatgen.alchemy.filters.SpeciesMaxDistFilter.test)


    * [pymatgen.alchemy.materials module](pymatgen.alchemy.md#module-pymatgen.alchemy.materials)


        * [`TransformedStructure`](pymatgen.alchemy.md#pymatgen.alchemy.materials.TransformedStructure)


            * [`TransformedStructure.append_filter()`](pymatgen.alchemy.md#pymatgen.alchemy.materials.TransformedStructure.append_filter)


            * [`TransformedStructure.append_transformation()`](pymatgen.alchemy.md#pymatgen.alchemy.materials.TransformedStructure.append_transformation)


            * [`TransformedStructure.as_dict()`](pymatgen.alchemy.md#pymatgen.alchemy.materials.TransformedStructure.as_dict)


            * [`TransformedStructure.extend_transformations()`](pymatgen.alchemy.md#pymatgen.alchemy.materials.TransformedStructure.extend_transformations)


            * [`TransformedStructure.from_cif_str()`](pymatgen.alchemy.md#pymatgen.alchemy.materials.TransformedStructure.from_cif_str)


            * [`TransformedStructure.from_cif_string()`](pymatgen.alchemy.md#pymatgen.alchemy.materials.TransformedStructure.from_cif_string)


            * [`TransformedStructure.from_dict()`](pymatgen.alchemy.md#pymatgen.alchemy.materials.TransformedStructure.from_dict)


            * [`TransformedStructure.from_poscar_str()`](pymatgen.alchemy.md#pymatgen.alchemy.materials.TransformedStructure.from_poscar_str)


            * [`TransformedStructure.from_poscar_string()`](pymatgen.alchemy.md#pymatgen.alchemy.materials.TransformedStructure.from_poscar_string)


            * [`TransformedStructure.from_snl()`](pymatgen.alchemy.md#pymatgen.alchemy.materials.TransformedStructure.from_snl)


            * [`TransformedStructure.get_vasp_input()`](pymatgen.alchemy.md#pymatgen.alchemy.materials.TransformedStructure.get_vasp_input)


            * [`TransformedStructure.redo_next_change()`](pymatgen.alchemy.md#pymatgen.alchemy.materials.TransformedStructure.redo_next_change)


            * [`TransformedStructure.set_parameter()`](pymatgen.alchemy.md#pymatgen.alchemy.materials.TransformedStructure.set_parameter)


            * [`TransformedStructure.structures`](pymatgen.alchemy.md#pymatgen.alchemy.materials.TransformedStructure.structures)


            * [`TransformedStructure.to_snl()`](pymatgen.alchemy.md#pymatgen.alchemy.materials.TransformedStructure.to_snl)


            * [`TransformedStructure.undo_last_change()`](pymatgen.alchemy.md#pymatgen.alchemy.materials.TransformedStructure.undo_last_change)


            * [`TransformedStructure.was_modified`](pymatgen.alchemy.md#pymatgen.alchemy.materials.TransformedStructure.was_modified)


            * [`TransformedStructure.write_vasp_input()`](pymatgen.alchemy.md#pymatgen.alchemy.materials.TransformedStructure.write_vasp_input)


    * [pymatgen.alchemy.transmuters module](pymatgen.alchemy.md#module-pymatgen.alchemy.transmuters)


        * [`CifTransmuter`](pymatgen.alchemy.md#pymatgen.alchemy.transmuters.CifTransmuter)


            * [`CifTransmuter.from_filenames()`](pymatgen.alchemy.md#pymatgen.alchemy.transmuters.CifTransmuter.from_filenames)


        * [`PoscarTransmuter`](pymatgen.alchemy.md#pymatgen.alchemy.transmuters.PoscarTransmuter)


            * [`PoscarTransmuter.from_filenames()`](pymatgen.alchemy.md#pymatgen.alchemy.transmuters.PoscarTransmuter.from_filenames)


        * [`StandardTransmuter`](pymatgen.alchemy.md#pymatgen.alchemy.transmuters.StandardTransmuter)


            * [`StandardTransmuter.transformed_structures`](pymatgen.alchemy.md#pymatgen.alchemy.transmuters.StandardTransmuter.transformed_structures)


            * [`StandardTransmuter.add_tags()`](pymatgen.alchemy.md#pymatgen.alchemy.transmuters.StandardTransmuter.add_tags)


            * [`StandardTransmuter.append_transformation()`](pymatgen.alchemy.md#pymatgen.alchemy.transmuters.StandardTransmuter.append_transformation)


            * [`StandardTransmuter.append_transformed_structures()`](pymatgen.alchemy.md#pymatgen.alchemy.transmuters.StandardTransmuter.append_transformed_structures)


            * [`StandardTransmuter.apply_filter()`](pymatgen.alchemy.md#pymatgen.alchemy.transmuters.StandardTransmuter.apply_filter)


            * [`StandardTransmuter.extend_transformations()`](pymatgen.alchemy.md#pymatgen.alchemy.transmuters.StandardTransmuter.extend_transformations)


            * [`StandardTransmuter.from_structures()`](pymatgen.alchemy.md#pymatgen.alchemy.transmuters.StandardTransmuter.from_structures)


            * [`StandardTransmuter.redo_next_change()`](pymatgen.alchemy.md#pymatgen.alchemy.transmuters.StandardTransmuter.redo_next_change)


            * [`StandardTransmuter.set_parameter()`](pymatgen.alchemy.md#pymatgen.alchemy.transmuters.StandardTransmuter.set_parameter)


            * [`StandardTransmuter.undo_last_change()`](pymatgen.alchemy.md#pymatgen.alchemy.transmuters.StandardTransmuter.undo_last_change)


            * [`StandardTransmuter.write_vasp_input()`](pymatgen.alchemy.md#pymatgen.alchemy.transmuters.StandardTransmuter.write_vasp_input)


        * [`_apply_transformation()`](pymatgen.alchemy.md#pymatgen.alchemy.transmuters._apply_transformation)


        * [`batch_write_vasp_input()`](pymatgen.alchemy.md#pymatgen.alchemy.transmuters.batch_write_vasp_input)


* [pymatgen.analysis namespace](pymatgen.analysis.md)


    * [Subpackages](pymatgen.analysis.md#subpackages)


        * [pymatgen.analysis.chemenv package](pymatgen.analysis.chemenv.md)


            * [Subpackages](pymatgen.analysis.chemenv.md#subpackages)


                * [pymatgen.analysis.chemenv.connectivity package](pymatgen.analysis.chemenv.connectivity.md)




                    * [pymatgen.analysis.chemenv.connectivity.connected_components module](pymatgen.analysis.chemenv.connectivity.md#module-pymatgen.analysis.chemenv.connectivity.connected_components)


                        * [`ConnectedComponent`](pymatgen.analysis.chemenv.connectivity.md#pymatgen.analysis.chemenv.connectivity.connected_components.ConnectedComponent)


                        * [`draw_network()`](pymatgen.analysis.chemenv.connectivity.md#pymatgen.analysis.chemenv.connectivity.connected_components.draw_network)


                        * [`make_supergraph()`](pymatgen.analysis.chemenv.connectivity.md#pymatgen.analysis.chemenv.connectivity.connected_components.make_supergraph)


                    * [pymatgen.analysis.chemenv.connectivity.connectivity_finder module](pymatgen.analysis.chemenv.connectivity.md#module-pymatgen.analysis.chemenv.connectivity.connectivity_finder)


                        * [`ConnectivityFinder`](pymatgen.analysis.chemenv.connectivity.md#pymatgen.analysis.chemenv.connectivity.connectivity_finder.ConnectivityFinder)


                    * [pymatgen.analysis.chemenv.connectivity.environment_nodes module](pymatgen.analysis.chemenv.connectivity.md#module-pymatgen.analysis.chemenv.connectivity.environment_nodes)


                        * [`AbstractEnvironmentNode`](pymatgen.analysis.chemenv.connectivity.md#pymatgen.analysis.chemenv.connectivity.environment_nodes.AbstractEnvironmentNode)


                        * [`EnvironmentNode`](pymatgen.analysis.chemenv.connectivity.md#pymatgen.analysis.chemenv.connectivity.environment_nodes.EnvironmentNode)


                        * [`get_environment_node()`](pymatgen.analysis.chemenv.connectivity.md#pymatgen.analysis.chemenv.connectivity.environment_nodes.get_environment_node)


                    * [pymatgen.analysis.chemenv.connectivity.structure_connectivity module](pymatgen.analysis.chemenv.connectivity.md#module-pymatgen.analysis.chemenv.connectivity.structure_connectivity)


                        * [`StructureConnectivity`](pymatgen.analysis.chemenv.connectivity.md#pymatgen.analysis.chemenv.connectivity.structure_connectivity.StructureConnectivity)


                        * [`get_delta_image()`](pymatgen.analysis.chemenv.connectivity.md#pymatgen.analysis.chemenv.connectivity.structure_connectivity.get_delta_image)


                * [pymatgen.analysis.chemenv.coordination_environments package](pymatgen.analysis.chemenv.coordination_environments.md)


                    * [Subpackages](pymatgen.analysis.chemenv.coordination_environments.md#subpackages)


                        * [pymatgen.analysis.chemenv.coordination_environments.coordination_geometries_files package](pymatgen.analysis.chemenv.coordination_environments.coordination_geometries_files.md)




                    * [pymatgen.analysis.chemenv.coordination_environments.chemenv_strategies module](pymatgen.analysis.chemenv.coordination_environments.md#module-pymatgen.analysis.chemenv.coordination_environments.chemenv_strategies)


                        * [`AbstractChemenvStrategy`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.chemenv_strategies.AbstractChemenvStrategy)


                        * [`AdditionalConditionInt`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.chemenv_strategies.AdditionalConditionInt)


                        * [`AngleCutoffFloat`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.chemenv_strategies.AngleCutoffFloat)


                        * [`AngleNbSetWeight`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.chemenv_strategies.AngleNbSetWeight)


                        * [`AnglePlateauNbSetWeight`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.chemenv_strategies.AnglePlateauNbSetWeight)


                        * [`CNBiasNbSetWeight`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.chemenv_strategies.CNBiasNbSetWeight)


                        * [`CSMFloat`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.chemenv_strategies.CSMFloat)


                        * [`DeltaCSMNbSetWeight`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.chemenv_strategies.DeltaCSMNbSetWeight)


                        * [`DeltaDistanceNbSetWeight`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.chemenv_strategies.DeltaDistanceNbSetWeight)


                        * [`DistanceAngleAreaNbSetWeight`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.chemenv_strategies.DistanceAngleAreaNbSetWeight)


                        * [`DistanceCutoffFloat`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.chemenv_strategies.DistanceCutoffFloat)


                        * [`DistanceNbSetWeight`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.chemenv_strategies.DistanceNbSetWeight)


                        * [`DistancePlateauNbSetWeight`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.chemenv_strategies.DistancePlateauNbSetWeight)


                        * [`MultiWeightsChemenvStrategy`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.chemenv_strategies.MultiWeightsChemenvStrategy)


                        * [`NbSetWeight`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.chemenv_strategies.NbSetWeight)


                        * [`NormalizedAngleDistanceNbSetWeight`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.chemenv_strategies.NormalizedAngleDistanceNbSetWeight)


                        * [`SelfCSMNbSetWeight`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.chemenv_strategies.SelfCSMNbSetWeight)


                        * [`SimpleAbundanceChemenvStrategy`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.chemenv_strategies.SimpleAbundanceChemenvStrategy)


                        * [`SimplestChemenvStrategy`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.chemenv_strategies.SimplestChemenvStrategy)


                        * [`StrategyOption`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.chemenv_strategies.StrategyOption)


                        * [`TargettedPenaltiedAbundanceChemenvStrategy`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.chemenv_strategies.TargettedPenaltiedAbundanceChemenvStrategy)


                        * [`WeightedNbSetChemenvStrategy`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.chemenv_strategies.WeightedNbSetChemenvStrategy)


                        * [`get_effective_csm()`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.chemenv_strategies.get_effective_csm)


                        * [`set_info()`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.chemenv_strategies.set_info)


                    * [pymatgen.analysis.chemenv.coordination_environments.coordination_geometries module](pymatgen.analysis.chemenv.coordination_environments.md#module-pymatgen.analysis.chemenv.coordination_environments.coordination_geometries)


                        * [`AbstractChemenvAlgorithm`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.coordination_geometries.AbstractChemenvAlgorithm)


                        * [`AllCoordinationGeometries`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.coordination_geometries.AllCoordinationGeometries)


                        * [`CoordinationGeometry`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.coordination_geometries.CoordinationGeometry)


                        * [`ExplicitPermutationsAlgorithm`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.coordination_geometries.ExplicitPermutationsAlgorithm)


                        * [`SeparationPlane`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.coordination_geometries.SeparationPlane)


                    * [pymatgen.analysis.chemenv.coordination_environments.coordination_geometry_finder module](pymatgen.analysis.chemenv.coordination_environments.md#module-pymatgen.analysis.chemenv.coordination_environments.coordination_geometry_finder)


                        * [`AbstractGeometry`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.coordination_geometry_finder.AbstractGeometry)


                        * [`LocalGeometryFinder`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.coordination_geometry_finder.LocalGeometryFinder)


                        * [`find_rotation()`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.coordination_geometry_finder.find_rotation)


                        * [`find_scaling_factor()`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.coordination_geometry_finder.find_scaling_factor)


                        * [`symmetry_measure()`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.coordination_geometry_finder.symmetry_measure)


                    * [pymatgen.analysis.chemenv.coordination_environments.structure_environments module](pymatgen.analysis.chemenv.coordination_environments.md#module-pymatgen.analysis.chemenv.coordination_environments.structure_environments)


                        * [`ChemicalEnvironments`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.structure_environments.ChemicalEnvironments)


                        * [`LightStructureEnvironments`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.structure_environments.LightStructureEnvironments)


                        * [`StructureEnvironments`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.structure_environments.StructureEnvironments)


                    * [pymatgen.analysis.chemenv.coordination_environments.voronoi module](pymatgen.analysis.chemenv.coordination_environments.md#module-pymatgen.analysis.chemenv.coordination_environments.voronoi)


                        * [`DetailedVoronoiContainer`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.voronoi.DetailedVoronoiContainer)


                        * [`from_bson_voronoi_list2()`](pymatgen.analysis.chemenv.coordination_environments.md#pymatgen.analysis.chemenv.coordination_environments.voronoi.from_bson_voronoi_list2)


                * [pymatgen.analysis.chemenv.utils package](pymatgen.analysis.chemenv.utils.md)




                    * [pymatgen.analysis.chemenv.utils.chemenv_config module](pymatgen.analysis.chemenv.utils.md#module-pymatgen.analysis.chemenv.utils.chemenv_config)


                        * [`ChemEnvConfig`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.chemenv_config.ChemEnvConfig)


                    * [pymatgen.analysis.chemenv.utils.chemenv_errors module](pymatgen.analysis.chemenv.utils.md#module-pymatgen.analysis.chemenv.utils.chemenv_errors)


                        * [`AbstractChemenvError`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.chemenv_errors.AbstractChemenvError)


                        * [`ChemenvError`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.chemenv_errors.ChemenvError)


                        * [`EquivalentSiteSearchError`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.chemenv_errors.EquivalentSiteSearchError)


                        * [`NeighborsNotComputedChemenvError`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.chemenv_errors.NeighborsNotComputedChemenvError)


                        * [`SolidAngleError`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.chemenv_errors.SolidAngleError)


                    * [pymatgen.analysis.chemenv.utils.coordination_geometry_utils module](pymatgen.analysis.chemenv.utils.md#module-pymatgen.analysis.chemenv.utils.coordination_geometry_utils)


                        * [`Plane`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.coordination_geometry_utils.Plane)


                        * [`anticlockwise_sort()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.coordination_geometry_utils.anticlockwise_sort)


                        * [`anticlockwise_sort_indices()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.coordination_geometry_utils.anticlockwise_sort_indices)


                        * [`changebasis()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.coordination_geometry_utils.changebasis)


                        * [`collinear()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.coordination_geometry_utils.collinear)


                        * [`diamond_functions()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.coordination_geometry_utils.diamond_functions)


                        * [`function_comparison()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.coordination_geometry_utils.function_comparison)


                        * [`get_lower_and_upper_f()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.coordination_geometry_utils.get_lower_and_upper_f)


                        * [`is_anion_cation_bond()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.coordination_geometry_utils.is_anion_cation_bond)


                        * [`matrixTimesVector()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.coordination_geometry_utils.matrixTimesVector)


                        * [`quarter_ellipsis_functions()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.coordination_geometry_utils.quarter_ellipsis_functions)


                        * [`rectangle_surface_intersection()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.coordination_geometry_utils.rectangle_surface_intersection)


                        * [`rotateCoords()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.coordination_geometry_utils.rotateCoords)


                        * [`rotateCoordsOpt()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.coordination_geometry_utils.rotateCoordsOpt)


                        * [`separation_in_list()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.coordination_geometry_utils.separation_in_list)


                        * [`solid_angle()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.coordination_geometry_utils.solid_angle)


                        * [`sort_separation()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.coordination_geometry_utils.sort_separation)


                        * [`sort_separation_tuple()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.coordination_geometry_utils.sort_separation_tuple)


                        * [`spline_functions()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.coordination_geometry_utils.spline_functions)


                        * [`vectorsToMatrix()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.coordination_geometry_utils.vectorsToMatrix)


                    * [pymatgen.analysis.chemenv.utils.defs_utils module](pymatgen.analysis.chemenv.utils.md#module-pymatgen.analysis.chemenv.utils.defs_utils)


                        * [`AdditionalConditions`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.defs_utils.AdditionalConditions)


                    * [pymatgen.analysis.chemenv.utils.func_utils module](pymatgen.analysis.chemenv.utils.md#module-pymatgen.analysis.chemenv.utils.func_utils)


                        * [`AbstractRatioFunction`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.func_utils.AbstractRatioFunction)


                        * [`CSMFiniteRatioFunction`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.func_utils.CSMFiniteRatioFunction)


                        * [`CSMInfiniteRatioFunction`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.func_utils.CSMInfiniteRatioFunction)


                        * [`DeltaCSMRatioFunction`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.func_utils.DeltaCSMRatioFunction)


                        * [`RatioFunction`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.func_utils.RatioFunction)


                    * [pymatgen.analysis.chemenv.utils.graph_utils module](pymatgen.analysis.chemenv.utils.md#module-pymatgen.analysis.chemenv.utils.graph_utils)


                        * [`MultiGraphCycle`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.graph_utils.MultiGraphCycle)


                        * [`SimpleGraphCycle`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.graph_utils.SimpleGraphCycle)


                        * [`_c2index_isreverse()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.graph_utils._c2index_isreverse)


                        * [`get_all_elementary_cycles()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.graph_utils.get_all_elementary_cycles)


                        * [`get_all_simple_paths_edges()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.graph_utils.get_all_simple_paths_edges)


                        * [`get_delta()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.graph_utils.get_delta)


                    * [pymatgen.analysis.chemenv.utils.math_utils module](pymatgen.analysis.chemenv.utils.md#module-pymatgen.analysis.chemenv.utils.math_utils)


                        * [`_append_es2sequences()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.math_utils._append_es2sequences)


                        * [`_cartesian_product()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.math_utils._cartesian_product)


                        * [`_factor_generator()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.math_utils._factor_generator)


                        * [`cosinus_step()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.math_utils.cosinus_step)


                        * [`divisors()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.math_utils.divisors)


                        * [`get_center_of_arc()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.math_utils.get_center_of_arc)


                        * [`get_linearly_independent_vectors()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.math_utils.get_linearly_independent_vectors)


                        * [`normal_cdf_step()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.math_utils.normal_cdf_step)


                        * [`power2_decreasing_exp()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.math_utils.power2_decreasing_exp)


                        * [`power2_inverse_decreasing()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.math_utils.power2_inverse_decreasing)


                        * [`power2_inverse_power2_decreasing()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.math_utils.power2_inverse_power2_decreasing)


                        * [`power2_inverse_powern_decreasing()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.math_utils.power2_inverse_powern_decreasing)


                        * [`power2_tangent_decreasing()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.math_utils.power2_tangent_decreasing)


                        * [`power3_step()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.math_utils.power3_step)


                        * [`powern_decreasing()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.math_utils.powern_decreasing)


                        * [`powern_parts_step()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.math_utils.powern_parts_step)


                        * [`prime_factors()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.math_utils.prime_factors)


                        * [`scale_and_clamp()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.math_utils.scale_and_clamp)


                        * [`smootherstep()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.math_utils.smootherstep)


                        * [`smoothstep()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.math_utils.smoothstep)


                    * [pymatgen.analysis.chemenv.utils.scripts_utils module](pymatgen.analysis.chemenv.utils.md#module-pymatgen.analysis.chemenv.utils.scripts_utils)


                        * [`compute_environments()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.scripts_utils.compute_environments)


                        * [`draw_cg()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.scripts_utils.draw_cg)


                        * [`visualize()`](pymatgen.analysis.chemenv.utils.md#pymatgen.analysis.chemenv.utils.scripts_utils.visualize)


        * [pymatgen.analysis.diffraction package](pymatgen.analysis.diffraction.md)




            * [pymatgen.analysis.diffraction.core module](pymatgen.analysis.diffraction.md#module-pymatgen.analysis.diffraction.core)


                * [`AbstractDiffractionPatternCalculator`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.core.AbstractDiffractionPatternCalculator)


                    * [`AbstractDiffractionPatternCalculator.SCALED_INTENSITY_TOL`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.core.AbstractDiffractionPatternCalculator.SCALED_INTENSITY_TOL)


                    * [`AbstractDiffractionPatternCalculator.TWO_THETA_TOL`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.core.AbstractDiffractionPatternCalculator.TWO_THETA_TOL)


                    * [`AbstractDiffractionPatternCalculator._abc_impl`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.core.AbstractDiffractionPatternCalculator._abc_impl)


                    * [`AbstractDiffractionPatternCalculator.get_pattern()`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.core.AbstractDiffractionPatternCalculator.get_pattern)


                    * [`AbstractDiffractionPatternCalculator.get_plot()`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.core.AbstractDiffractionPatternCalculator.get_plot)


                    * [`AbstractDiffractionPatternCalculator.plot_structures()`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.core.AbstractDiffractionPatternCalculator.plot_structures)


                    * [`AbstractDiffractionPatternCalculator.show_plot()`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.core.AbstractDiffractionPatternCalculator.show_plot)


                * [`DiffractionPattern`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.core.DiffractionPattern)


                    * [`DiffractionPattern.XLABEL`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.core.DiffractionPattern.XLABEL)


                    * [`DiffractionPattern.YLABEL`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.core.DiffractionPattern.YLABEL)


                * [`get_unique_families()`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.core.get_unique_families)


            * [pymatgen.analysis.diffraction.neutron module](pymatgen.analysis.diffraction.md#module-pymatgen.analysis.diffraction.neutron)


                * [`NDCalculator`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.neutron.NDCalculator)


                    * [`NDCalculator._abc_impl`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.neutron.NDCalculator._abc_impl)


                    * [`NDCalculator.get_pattern()`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.neutron.NDCalculator.get_pattern)


            * [pymatgen.analysis.diffraction.tem module](pymatgen.analysis.diffraction.md#module-pymatgen.analysis.diffraction.tem)


                * [`TEMCalculator`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.tem.TEMCalculator)


                    * [`TEMCalculator._abc_impl`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.tem.TEMCalculator._abc_impl)


                    * [`TEMCalculator.bragg_angles()`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.tem.TEMCalculator.bragg_angles)


                    * [`TEMCalculator.cell_intensity()`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.tem.TEMCalculator.cell_intensity)


                    * [`TEMCalculator.cell_scattering_factors()`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.tem.TEMCalculator.cell_scattering_factors)


                    * [`TEMCalculator.electron_scattering_factors()`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.tem.TEMCalculator.electron_scattering_factors)


                    * [`TEMCalculator.generate_points()`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.tem.TEMCalculator.generate_points)


                    * [`TEMCalculator.get_first_point()`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.tem.TEMCalculator.get_first_point)


                    * [`TEMCalculator.get_interplanar_angle()`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.tem.TEMCalculator.get_interplanar_angle)


                    * [`TEMCalculator.get_interplanar_spacings()`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.tem.TEMCalculator.get_interplanar_spacings)


                    * [`TEMCalculator.get_pattern()`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.tem.TEMCalculator.get_pattern)


                    * [`TEMCalculator.get_plot_2d()`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.tem.TEMCalculator.get_plot_2d)


                    * [`TEMCalculator.get_plot_2d_concise()`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.tem.TEMCalculator.get_plot_2d_concise)


                    * [`TEMCalculator.get_plot_coeffs()`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.tem.TEMCalculator.get_plot_coeffs)


                    * [`TEMCalculator.get_positions()`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.tem.TEMCalculator.get_positions)


                    * [`TEMCalculator.get_s2()`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.tem.TEMCalculator.get_s2)


                    * [`TEMCalculator.is_parallel()`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.tem.TEMCalculator.is_parallel)


                    * [`TEMCalculator.normalized_cell_intensity()`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.tem.TEMCalculator.normalized_cell_intensity)


                    * [`TEMCalculator.tem_dots()`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.tem.TEMCalculator.tem_dots)


                    * [`TEMCalculator.wavelength_rel()`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.tem.TEMCalculator.wavelength_rel)


                    * [`TEMCalculator.x_ray_factors()`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.tem.TEMCalculator.x_ray_factors)


                    * [`TEMCalculator.zone_axis_filter()`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.tem.TEMCalculator.zone_axis_filter)


            * [pymatgen.analysis.diffraction.xrd module](pymatgen.analysis.diffraction.md#module-pymatgen.analysis.diffraction.xrd)


                * [`XRDCalculator`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.xrd.XRDCalculator)


                    * [`XRDCalculator.AVAILABLE_RADIATION`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.xrd.XRDCalculator.AVAILABLE_RADIATION)


                    * [`XRDCalculator._abc_impl`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.xrd.XRDCalculator._abc_impl)


                    * [`XRDCalculator.get_pattern()`](pymatgen.analysis.diffraction.md#pymatgen.analysis.diffraction.xrd.XRDCalculator.get_pattern)


        * [pymatgen.analysis.elasticity package](pymatgen.analysis.elasticity.md)




            * [pymatgen.analysis.elasticity.elastic module](pymatgen.analysis.elasticity.md#module-pymatgen.analysis.elasticity.elastic)


                * [`ComplianceTensor`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ComplianceTensor)


                * [`ElasticTensor`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensor)


                    * [`ElasticTensor.cahill_thermalcond()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensor.cahill_thermalcond)


                    * [`ElasticTensor.clarke_thermalcond()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensor.clarke_thermalcond)


                    * [`ElasticTensor.compliance_tensor`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensor.compliance_tensor)


                    * [`ElasticTensor.debye_temperature()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensor.debye_temperature)


                    * [`ElasticTensor.directional_elastic_mod()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensor.directional_elastic_mod)


                    * [`ElasticTensor.directional_poisson_ratio()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensor.directional_poisson_ratio)


                    * [`ElasticTensor.from_independent_strains()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensor.from_independent_strains)


                    * [`ElasticTensor.from_pseudoinverse()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensor.from_pseudoinverse)


                    * [`ElasticTensor.g_reuss`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensor.g_reuss)


                    * [`ElasticTensor.g_voigt`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensor.g_voigt)


                    * [`ElasticTensor.g_vrh`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensor.g_vrh)


                    * [`ElasticTensor.get_structure_property_dict()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensor.get_structure_property_dict)


                    * [`ElasticTensor.green_kristoffel()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensor.green_kristoffel)


                    * [`ElasticTensor.homogeneous_poisson`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensor.homogeneous_poisson)


                    * [`ElasticTensor.k_reuss`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensor.k_reuss)


                    * [`ElasticTensor.k_voigt`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensor.k_voigt)


                    * [`ElasticTensor.k_vrh`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensor.k_vrh)


                    * [`ElasticTensor.long_v()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensor.long_v)


                    * [`ElasticTensor.property_dict`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensor.property_dict)


                    * [`ElasticTensor.snyder_ac()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensor.snyder_ac)


                    * [`ElasticTensor.snyder_opt()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensor.snyder_opt)


                    * [`ElasticTensor.snyder_total()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensor.snyder_total)


                    * [`ElasticTensor.trans_v()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensor.trans_v)


                    * [`ElasticTensor.universal_anisotropy`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensor.universal_anisotropy)


                    * [`ElasticTensor.y_mod`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensor.y_mod)


                * [`ElasticTensorExpansion`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensorExpansion)


                    * [`ElasticTensorExpansion._abc_impl`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensorExpansion._abc_impl)


                    * [`ElasticTensorExpansion.calculate_stress()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensorExpansion.calculate_stress)


                    * [`ElasticTensorExpansion.energy_density()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensorExpansion.energy_density)


                    * [`ElasticTensorExpansion.from_diff_fit()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensorExpansion.from_diff_fit)


                    * [`ElasticTensorExpansion.get_compliance_expansion()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensorExpansion.get_compliance_expansion)


                    * [`ElasticTensorExpansion.get_effective_ecs()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensorExpansion.get_effective_ecs)


                    * [`ElasticTensorExpansion.get_ggt()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensorExpansion.get_ggt)


                    * [`ElasticTensorExpansion.get_gruneisen_parameter()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensorExpansion.get_gruneisen_parameter)


                    * [`ElasticTensorExpansion.get_heat_capacity()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensorExpansion.get_heat_capacity)


                    * [`ElasticTensorExpansion.get_stability_criteria()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensorExpansion.get_stability_criteria)


                    * [`ElasticTensorExpansion.get_strain_from_stress()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensorExpansion.get_strain_from_stress)


                    * [`ElasticTensorExpansion.get_symmetric_wallace_tensor()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensorExpansion.get_symmetric_wallace_tensor)


                    * [`ElasticTensorExpansion.get_tgt()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensorExpansion.get_tgt)


                    * [`ElasticTensorExpansion.get_wallace_tensor()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensorExpansion.get_wallace_tensor)


                    * [`ElasticTensorExpansion.get_yield_stress()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensorExpansion.get_yield_stress)


                    * [`ElasticTensorExpansion.omega()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensorExpansion.omega)


                    * [`ElasticTensorExpansion.order`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensorExpansion.order)


                    * [`ElasticTensorExpansion.thermal_expansion_coeff()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.ElasticTensorExpansion.thermal_expansion_coeff)


                * [`NthOrderElasticTensor`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.NthOrderElasticTensor)


                    * [`NthOrderElasticTensor.GPa_to_eV_A3`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.NthOrderElasticTensor.GPa_to_eV_A3)


                    * [`NthOrderElasticTensor.calculate_stress()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.NthOrderElasticTensor.calculate_stress)


                    * [`NthOrderElasticTensor.energy_density()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.NthOrderElasticTensor.energy_density)


                    * [`NthOrderElasticTensor.from_diff_fit()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.NthOrderElasticTensor.from_diff_fit)


                    * [`NthOrderElasticTensor.order`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.NthOrderElasticTensor.order)


                    * [`NthOrderElasticTensor.symbol`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.NthOrderElasticTensor.symbol)


                * [`diff_fit()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.diff_fit)


                * [`find_eq_stress()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.find_eq_stress)


                * [`generate_pseudo()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.generate_pseudo)


                * [`get_diff_coeff()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.get_diff_coeff)


                * [`get_strain_state_dict()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.get_strain_state_dict)


                * [`get_symbol_list()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.get_symbol_list)


                * [`raise_if_unphysical()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.raise_if_unphysical)


                * [`subs()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.elastic.subs)


            * [pymatgen.analysis.elasticity.strain module](pymatgen.analysis.elasticity.md#module-pymatgen.analysis.elasticity.strain)


                * [`Deformation`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.strain.Deformation)


                    * [`Deformation.apply_to_structure()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.strain.Deformation.apply_to_structure)


                    * [`Deformation.from_index_amount()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.strain.Deformation.from_index_amount)


                    * [`Deformation.get_perturbed_indices()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.strain.Deformation.get_perturbed_indices)


                    * [`Deformation.green_lagrange_strain`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.strain.Deformation.green_lagrange_strain)


                    * [`Deformation.is_independent()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.strain.Deformation.is_independent)


                    * [`Deformation.symbol`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.strain.Deformation.symbol)


                * [`DeformedStructureSet`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.strain.DeformedStructureSet)


                    * [`DeformedStructureSet._abc_impl`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.strain.DeformedStructureSet._abc_impl)


                * [`Strain`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.strain.Strain)


                    * [`Strain.from_deformation()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.strain.Strain.from_deformation)


                    * [`Strain.from_index_amount()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.strain.Strain.from_index_amount)


                    * [`Strain.get_deformation_matrix()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.strain.Strain.get_deformation_matrix)


                    * [`Strain.symbol`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.strain.Strain.symbol)


                    * [`Strain.von_mises_strain`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.strain.Strain.von_mises_strain)


                * [`convert_strain_to_deformation()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.strain.convert_strain_to_deformation)


            * [pymatgen.analysis.elasticity.stress module](pymatgen.analysis.elasticity.md#module-pymatgen.analysis.elasticity.stress)


                * [`Stress`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.stress.Stress)


                    * [`Stress.dev_principal_invariants`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.stress.Stress.dev_principal_invariants)


                    * [`Stress.deviator_stress`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.stress.Stress.deviator_stress)


                    * [`Stress.mean_stress`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.stress.Stress.mean_stress)


                    * [`Stress.piola_kirchoff_1()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.stress.Stress.piola_kirchoff_1)


                    * [`Stress.piola_kirchoff_2()`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.stress.Stress.piola_kirchoff_2)


                    * [`Stress.symbol`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.stress.Stress.symbol)


                    * [`Stress.von_mises`](pymatgen.analysis.elasticity.md#pymatgen.analysis.elasticity.stress.Stress.von_mises)


        * [pymatgen.analysis.ferroelectricity package](pymatgen.analysis.ferroelectricity.md)




            * [pymatgen.analysis.ferroelectricity.polarization module](pymatgen.analysis.ferroelectricity.md#module-pymatgen.analysis.ferroelectricity.polarization)


                * [`EnergyTrend`](pymatgen.analysis.ferroelectricity.md#pymatgen.analysis.ferroelectricity.polarization.EnergyTrend)


                    * [`EnergyTrend.endpoints_minima()`](pymatgen.analysis.ferroelectricity.md#pymatgen.analysis.ferroelectricity.polarization.EnergyTrend.endpoints_minima)


                    * [`EnergyTrend.max_spline_jump()`](pymatgen.analysis.ferroelectricity.md#pymatgen.analysis.ferroelectricity.polarization.EnergyTrend.max_spline_jump)


                    * [`EnergyTrend.smoothness()`](pymatgen.analysis.ferroelectricity.md#pymatgen.analysis.ferroelectricity.polarization.EnergyTrend.smoothness)


                    * [`EnergyTrend.spline()`](pymatgen.analysis.ferroelectricity.md#pymatgen.analysis.ferroelectricity.polarization.EnergyTrend.spline)


                * [`Polarization`](pymatgen.analysis.ferroelectricity.md#pymatgen.analysis.ferroelectricity.polarization.Polarization)


                    * [`Polarization.from_outcars_and_structures()`](pymatgen.analysis.ferroelectricity.md#pymatgen.analysis.ferroelectricity.polarization.Polarization.from_outcars_and_structures)


                    * [`Polarization.get_lattice_quanta()`](pymatgen.analysis.ferroelectricity.md#pymatgen.analysis.ferroelectricity.polarization.Polarization.get_lattice_quanta)


                    * [`Polarization.get_pelecs_and_pions()`](pymatgen.analysis.ferroelectricity.md#pymatgen.analysis.ferroelectricity.polarization.Polarization.get_pelecs_and_pions)


                    * [`Polarization.get_polarization_change()`](pymatgen.analysis.ferroelectricity.md#pymatgen.analysis.ferroelectricity.polarization.Polarization.get_polarization_change)


                    * [`Polarization.get_polarization_change_norm()`](pymatgen.analysis.ferroelectricity.md#pymatgen.analysis.ferroelectricity.polarization.Polarization.get_polarization_change_norm)


                    * [`Polarization.get_same_branch_polarization_data()`](pymatgen.analysis.ferroelectricity.md#pymatgen.analysis.ferroelectricity.polarization.Polarization.get_same_branch_polarization_data)


                    * [`Polarization.max_spline_jumps()`](pymatgen.analysis.ferroelectricity.md#pymatgen.analysis.ferroelectricity.polarization.Polarization.max_spline_jumps)


                    * [`Polarization.same_branch_splines()`](pymatgen.analysis.ferroelectricity.md#pymatgen.analysis.ferroelectricity.polarization.Polarization.same_branch_splines)


                    * [`Polarization.smoothness()`](pymatgen.analysis.ferroelectricity.md#pymatgen.analysis.ferroelectricity.polarization.Polarization.smoothness)


                * [`PolarizationLattice`](pymatgen.analysis.ferroelectricity.md#pymatgen.analysis.ferroelectricity.polarization.PolarizationLattice)


                    * [`PolarizationLattice._abc_impl`](pymatgen.analysis.ferroelectricity.md#pymatgen.analysis.ferroelectricity.polarization.PolarizationLattice._abc_impl)


                    * [`PolarizationLattice._properties`](pymatgen.analysis.ferroelectricity.md#pymatgen.analysis.ferroelectricity.polarization.PolarizationLattice._properties)


                    * [`PolarizationLattice.get_nearest_site()`](pymatgen.analysis.ferroelectricity.md#pymatgen.analysis.ferroelectricity.polarization.PolarizationLattice.get_nearest_site)


                * [`calc_ionic()`](pymatgen.analysis.ferroelectricity.md#pymatgen.analysis.ferroelectricity.polarization.calc_ionic)


                * [`get_total_ionic_dipole()`](pymatgen.analysis.ferroelectricity.md#pymatgen.analysis.ferroelectricity.polarization.get_total_ionic_dipole)


                * [`zval_dict_from_potcar()`](pymatgen.analysis.ferroelectricity.md#pymatgen.analysis.ferroelectricity.polarization.zval_dict_from_potcar)


        * [pymatgen.analysis.gb package](pymatgen.analysis.gb.md)




            * [pymatgen.analysis.gb.grain module](pymatgen.analysis.gb.md#module-pymatgen.analysis.gb.grain)


                * [`GrainBoundary`](pymatgen.analysis.gb.md#pymatgen.analysis.gb.grain.GrainBoundary)


                    * [`GrainBoundary._abc_impl`](pymatgen.analysis.gb.md#pymatgen.analysis.gb.grain.GrainBoundary._abc_impl)


                    * [`GrainBoundary._properties`](pymatgen.analysis.gb.md#pymatgen.analysis.gb.grain.GrainBoundary._properties)


                    * [`GrainBoundary.as_dict()`](pymatgen.analysis.gb.md#pymatgen.analysis.gb.grain.GrainBoundary.as_dict)


                    * [`GrainBoundary.bottom_grain`](pymatgen.analysis.gb.md#pymatgen.analysis.gb.grain.GrainBoundary.bottom_grain)


                    * [`GrainBoundary.coincidents`](pymatgen.analysis.gb.md#pymatgen.analysis.gb.grain.GrainBoundary.coincidents)


                    * [`GrainBoundary.copy()`](pymatgen.analysis.gb.md#pymatgen.analysis.gb.grain.GrainBoundary.copy)


                    * [`GrainBoundary.from_dict()`](pymatgen.analysis.gb.md#pymatgen.analysis.gb.grain.GrainBoundary.from_dict)


                    * [`GrainBoundary.get_sorted_structure()`](pymatgen.analysis.gb.md#pymatgen.analysis.gb.grain.GrainBoundary.get_sorted_structure)


                    * [`GrainBoundary.sigma`](pymatgen.analysis.gb.md#pymatgen.analysis.gb.grain.GrainBoundary.sigma)


                    * [`GrainBoundary.sigma_from_site_prop`](pymatgen.analysis.gb.md#pymatgen.analysis.gb.grain.GrainBoundary.sigma_from_site_prop)


                    * [`GrainBoundary.top_grain`](pymatgen.analysis.gb.md#pymatgen.analysis.gb.grain.GrainBoundary.top_grain)


                * [`GrainBoundaryGenerator`](pymatgen.analysis.gb.md#pymatgen.analysis.gb.grain.GrainBoundaryGenerator)


                    * [`GrainBoundaryGenerator.enum_possible_plane_cubic()`](pymatgen.analysis.gb.md#pymatgen.analysis.gb.grain.GrainBoundaryGenerator.enum_possible_plane_cubic)


                    * [`GrainBoundaryGenerator.enum_sigma_cubic()`](pymatgen.analysis.gb.md#pymatgen.analysis.gb.grain.GrainBoundaryGenerator.enum_sigma_cubic)


                    * [`GrainBoundaryGenerator.enum_sigma_hex()`](pymatgen.analysis.gb.md#pymatgen.analysis.gb.grain.GrainBoundaryGenerator.enum_sigma_hex)


                    * [`GrainBoundaryGenerator.enum_sigma_ort()`](pymatgen.analysis.gb.md#pymatgen.analysis.gb.grain.GrainBoundaryGenerator.enum_sigma_ort)


                    * [`GrainBoundaryGenerator.enum_sigma_rho()`](pymatgen.analysis.gb.md#pymatgen.analysis.gb.grain.GrainBoundaryGenerator.enum_sigma_rho)


                    * [`GrainBoundaryGenerator.enum_sigma_tet()`](pymatgen.analysis.gb.md#pymatgen.analysis.gb.grain.GrainBoundaryGenerator.enum_sigma_tet)


                    * [`GrainBoundaryGenerator.gb_from_parameters()`](pymatgen.analysis.gb.md#pymatgen.analysis.gb.grain.GrainBoundaryGenerator.gb_from_parameters)


                    * [`GrainBoundaryGenerator.get_ratio()`](pymatgen.analysis.gb.md#pymatgen.analysis.gb.grain.GrainBoundaryGenerator.get_ratio)


                    * [`GrainBoundaryGenerator.get_rotation_angle_from_sigma()`](pymatgen.analysis.gb.md#pymatgen.analysis.gb.grain.GrainBoundaryGenerator.get_rotation_angle_from_sigma)


                    * [`GrainBoundaryGenerator.get_trans_mat()`](pymatgen.analysis.gb.md#pymatgen.analysis.gb.grain.GrainBoundaryGenerator.get_trans_mat)


                    * [`GrainBoundaryGenerator.reduce_mat()`](pymatgen.analysis.gb.md#pymatgen.analysis.gb.grain.GrainBoundaryGenerator.reduce_mat)


                    * [`GrainBoundaryGenerator.slab_from_csl()`](pymatgen.analysis.gb.md#pymatgen.analysis.gb.grain.GrainBoundaryGenerator.slab_from_csl)


                    * [`GrainBoundaryGenerator.vec_to_surface()`](pymatgen.analysis.gb.md#pymatgen.analysis.gb.grain.GrainBoundaryGenerator.vec_to_surface)


                * [`fix_pbc()`](pymatgen.analysis.gb.md#pymatgen.analysis.gb.grain.fix_pbc)


                * [`symm_group_cubic()`](pymatgen.analysis.gb.md#pymatgen.analysis.gb.grain.symm_group_cubic)


        * [pymatgen.analysis.interfaces package](pymatgen.analysis.interfaces.md)




            * [pymatgen.analysis.interfaces.coherent_interfaces module](pymatgen.analysis.interfaces.md#module-pymatgen.analysis.interfaces.coherent_interfaces)


                * [`CoherentInterfaceBuilder`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.coherent_interfaces.CoherentInterfaceBuilder)


                    * [`CoherentInterfaceBuilder._find_matches()`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.coherent_interfaces.CoherentInterfaceBuilder._find_matches)


                    * [`CoherentInterfaceBuilder._find_terminations()`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.coherent_interfaces.CoherentInterfaceBuilder._find_terminations)


                    * [`CoherentInterfaceBuilder.get_interfaces()`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.coherent_interfaces.CoherentInterfaceBuilder.get_interfaces)


                * [`from_2d_to_3d()`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.coherent_interfaces.from_2d_to_3d)


                * [`get_2d_transform()`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.coherent_interfaces.get_2d_transform)


                * [`get_rot_3d_for_2d()`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.coherent_interfaces.get_rot_3d_for_2d)


            * [pymatgen.analysis.interfaces.substrate_analyzer module](pymatgen.analysis.interfaces.md#module-pymatgen.analysis.interfaces.substrate_analyzer)


                * [`SubstrateAnalyzer`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.substrate_analyzer.SubstrateAnalyzer)


                    * [`SubstrateAnalyzer.calculate()`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.substrate_analyzer.SubstrateAnalyzer.calculate)


                    * [`SubstrateAnalyzer.generate_surface_vectors()`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.substrate_analyzer.SubstrateAnalyzer.generate_surface_vectors)


                * [`SubstrateMatch`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.substrate_analyzer.SubstrateMatch)


                    * [`SubstrateMatch.elastic_energy`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.substrate_analyzer.SubstrateMatch.elastic_energy)


                    * [`SubstrateMatch.film_miller`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.substrate_analyzer.SubstrateMatch.film_miller)


                    * [`SubstrateMatch.from_zsl()`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.substrate_analyzer.SubstrateMatch.from_zsl)


                    * [`SubstrateMatch.ground_state_energy`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.substrate_analyzer.SubstrateMatch.ground_state_energy)


                    * [`SubstrateMatch.strain`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.substrate_analyzer.SubstrateMatch.strain)


                    * [`SubstrateMatch.substrate_miller`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.substrate_analyzer.SubstrateMatch.substrate_miller)


                    * [`SubstrateMatch.total_energy`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.substrate_analyzer.SubstrateMatch.total_energy)


                    * [`SubstrateMatch.von_mises_strain`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.substrate_analyzer.SubstrateMatch.von_mises_strain)


            * [pymatgen.analysis.interfaces.zsl module](pymatgen.analysis.interfaces.md#module-pymatgen.analysis.interfaces.zsl)


                * [`ZSLGenerator`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.zsl.ZSLGenerator)


                    * [`ZSLGenerator.generate_sl_transformation_sets()`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.zsl.ZSLGenerator.generate_sl_transformation_sets)


                    * [`ZSLGenerator.get_equiv_transformations()`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.zsl.ZSLGenerator.get_equiv_transformations)


                * [`ZSLMatch`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.zsl.ZSLMatch)


                    * [`ZSLMatch.film_sl_vectors`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.zsl.ZSLMatch.film_sl_vectors)


                    * [`ZSLMatch.film_transformation`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.zsl.ZSLMatch.film_transformation)


                    * [`ZSLMatch.film_vectors`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.zsl.ZSLMatch.film_vectors)


                    * [`ZSLMatch.match_area`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.zsl.ZSLMatch.match_area)


                    * [`ZSLMatch.match_transformation`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.zsl.ZSLMatch.match_transformation)


                    * [`ZSLMatch.substrate_sl_vectors`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.zsl.ZSLMatch.substrate_sl_vectors)


                    * [`ZSLMatch.substrate_transformation`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.zsl.ZSLMatch.substrate_transformation)


                    * [`ZSLMatch.substrate_vectors`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.zsl.ZSLMatch.substrate_vectors)


                * [`_bidirectional_same_vectors()`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.zsl._bidirectional_same_vectors)


                * [`_unidirectional_is_same_vectors()`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.zsl._unidirectional_is_same_vectors)


                * [`fast_norm()`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.zsl.fast_norm)


                * [`gen_sl_transform_matrices()`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.zsl.gen_sl_transform_matrices)


                * [`get_factors()`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.zsl.get_factors)


                * [`is_same_vectors()`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.zsl.is_same_vectors)


                * [`reduce_vectors()`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.zsl.reduce_vectors)


                * [`rel_angle()`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.zsl.rel_angle)


                * [`rel_strain()`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.zsl.rel_strain)


                * [`vec_angle()`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.zsl.vec_angle)


                * [`vec_area()`](pymatgen.analysis.interfaces.md#pymatgen.analysis.interfaces.zsl.vec_area)


        * [pymatgen.analysis.magnetism package](pymatgen.analysis.magnetism.md)




            * [pymatgen.analysis.magnetism.analyzer module](pymatgen.analysis.magnetism.md#module-pymatgen.analysis.magnetism.analyzer)


                * [`CollinearMagneticStructureAnalyzer`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.CollinearMagneticStructureAnalyzer)


                    * [`CollinearMagneticStructureAnalyzer._round_magmoms()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.CollinearMagneticStructureAnalyzer._round_magmoms)


                    * [`CollinearMagneticStructureAnalyzer.get_exchange_group_info()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.CollinearMagneticStructureAnalyzer.get_exchange_group_info)


                    * [`CollinearMagneticStructureAnalyzer.get_ferromagnetic_structure()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.CollinearMagneticStructureAnalyzer.get_ferromagnetic_structure)


                    * [`CollinearMagneticStructureAnalyzer.get_nonmagnetic_structure()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.CollinearMagneticStructureAnalyzer.get_nonmagnetic_structure)


                    * [`CollinearMagneticStructureAnalyzer.get_structure_with_only_magnetic_atoms()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.CollinearMagneticStructureAnalyzer.get_structure_with_only_magnetic_atoms)


                    * [`CollinearMagneticStructureAnalyzer.get_structure_with_spin()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.CollinearMagneticStructureAnalyzer.get_structure_with_spin)


                    * [`CollinearMagneticStructureAnalyzer.is_magnetic`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.CollinearMagneticStructureAnalyzer.is_magnetic)


                    * [`CollinearMagneticStructureAnalyzer.magmoms`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.CollinearMagneticStructureAnalyzer.magmoms)


                    * [`CollinearMagneticStructureAnalyzer.magnetic_species_and_magmoms`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.CollinearMagneticStructureAnalyzer.magnetic_species_and_magmoms)


                    * [`CollinearMagneticStructureAnalyzer.matches_ordering()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.CollinearMagneticStructureAnalyzer.matches_ordering)


                    * [`CollinearMagneticStructureAnalyzer.number_of_magnetic_sites`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.CollinearMagneticStructureAnalyzer.number_of_magnetic_sites)


                    * [`CollinearMagneticStructureAnalyzer.number_of_unique_magnetic_sites()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.CollinearMagneticStructureAnalyzer.number_of_unique_magnetic_sites)


                    * [`CollinearMagneticStructureAnalyzer.ordering`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.CollinearMagneticStructureAnalyzer.ordering)


                    * [`CollinearMagneticStructureAnalyzer.types_of_magnetic_specie`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.CollinearMagneticStructureAnalyzer.types_of_magnetic_specie)


                    * [`CollinearMagneticStructureAnalyzer.types_of_magnetic_species`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.CollinearMagneticStructureAnalyzer.types_of_magnetic_species)


                * [`MagneticDeformation`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.MagneticDeformation)


                    * [`MagneticDeformation._asdict()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.MagneticDeformation._asdict)


                    * [`MagneticDeformation._field_defaults`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.MagneticDeformation._field_defaults)


                    * [`MagneticDeformation._fields`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.MagneticDeformation._fields)


                    * [`MagneticDeformation._make()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.MagneticDeformation._make)


                    * [`MagneticDeformation._replace()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.MagneticDeformation._replace)


                    * [`MagneticDeformation.deformation`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.MagneticDeformation.deformation)


                    * [`MagneticDeformation.type`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.MagneticDeformation.type)


                * [`MagneticStructureEnumerator`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.MagneticStructureEnumerator)


                    * [`MagneticStructureEnumerator._generate_ordered_structures()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.MagneticStructureEnumerator._generate_ordered_structures)


                    * [`MagneticStructureEnumerator._generate_transformations()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.MagneticStructureEnumerator._generate_transformations)


                    * [`MagneticStructureEnumerator._sanitize_input_structure()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.MagneticStructureEnumerator._sanitize_input_structure)


                    * [`MagneticStructureEnumerator.available_strategies`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.MagneticStructureEnumerator.available_strategies)


                * [`Ordering`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.Ordering)


                    * [`Ordering.AFM`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.Ordering.AFM)


                    * [`Ordering.FM`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.Ordering.FM)


                    * [`Ordering.FiM`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.Ordering.FiM)


                    * [`Ordering.NM`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.Ordering.NM)


                    * [`Ordering.Unknown`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.Ordering.Unknown)


                * [`OverwriteMagmomMode`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.OverwriteMagmomMode)


                    * [`OverwriteMagmomMode.none`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.OverwriteMagmomMode.none)


                    * [`OverwriteMagmomMode.normalize`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.OverwriteMagmomMode.normalize)


                    * [`OverwriteMagmomMode.replace_all`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.OverwriteMagmomMode.replace_all)


                    * [`OverwriteMagmomMode.respect_sign`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.OverwriteMagmomMode.respect_sign)


                    * [`OverwriteMagmomMode.respect_zero`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.OverwriteMagmomMode.respect_zero)


                * [`magnetic_deformation()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.analyzer.magnetic_deformation)


            * [pymatgen.analysis.magnetism.heisenberg module](pymatgen.analysis.magnetism.md#module-pymatgen.analysis.magnetism.heisenberg)


                * [`HeisenbergMapper`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.heisenberg.HeisenbergMapper)


                    * [`HeisenbergMapper._get_exchange_df()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.heisenberg.HeisenbergMapper._get_exchange_df)


                    * [`HeisenbergMapper._get_graphs()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.heisenberg.HeisenbergMapper._get_graphs)


                    * [`HeisenbergMapper._get_j_exc()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.heisenberg.HeisenbergMapper._get_j_exc)


                    * [`HeisenbergMapper._get_nn_dict()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.heisenberg.HeisenbergMapper._get_nn_dict)


                    * [`HeisenbergMapper._get_unique_sites()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.heisenberg.HeisenbergMapper._get_unique_sites)


                    * [`HeisenbergMapper.estimate_exchange()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.heisenberg.HeisenbergMapper.estimate_exchange)


                    * [`HeisenbergMapper.get_exchange()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.heisenberg.HeisenbergMapper.get_exchange)


                    * [`HeisenbergMapper.get_heisenberg_model()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.heisenberg.HeisenbergMapper.get_heisenberg_model)


                    * [`HeisenbergMapper.get_interaction_graph()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.heisenberg.HeisenbergMapper.get_interaction_graph)


                    * [`HeisenbergMapper.get_low_energy_orderings()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.heisenberg.HeisenbergMapper.get_low_energy_orderings)


                    * [`HeisenbergMapper.get_mft_temperature()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.heisenberg.HeisenbergMapper.get_mft_temperature)


                * [`HeisenbergModel`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.heisenberg.HeisenbergModel)


                    * [`HeisenbergModel._get_j_exc()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.heisenberg.HeisenbergModel._get_j_exc)


                    * [`HeisenbergModel.as_dict()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.heisenberg.HeisenbergModel.as_dict)


                    * [`HeisenbergModel.from_dict()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.heisenberg.HeisenbergModel.from_dict)


                * [`HeisenbergScreener`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.heisenberg.HeisenbergScreener)


                    * [`HeisenbergScreener.screened_structures`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.heisenberg.HeisenbergScreener.screened_structures)


                    * [`HeisenbergScreener.screened_energies`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.heisenberg.HeisenbergScreener.screened_energies)


                    * [`HeisenbergScreener._do_cleanup()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.heisenberg.HeisenbergScreener._do_cleanup)


                    * [`HeisenbergScreener._do_screen()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.heisenberg.HeisenbergScreener._do_screen)


            * [pymatgen.analysis.magnetism.jahnteller module](pymatgen.analysis.magnetism.md#module-pymatgen.analysis.magnetism.jahnteller)


                * [`JahnTellerAnalyzer`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.jahnteller.JahnTellerAnalyzer)


                    * [`JahnTellerAnalyzer._estimate_spin_state()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.jahnteller.JahnTellerAnalyzer._estimate_spin_state)


                    * [`JahnTellerAnalyzer._get_number_of_d_electrons()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.jahnteller.JahnTellerAnalyzer._get_number_of_d_electrons)


                    * [`JahnTellerAnalyzer.get_analysis()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.jahnteller.JahnTellerAnalyzer.get_analysis)


                    * [`JahnTellerAnalyzer.get_analysis_and_structure()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.jahnteller.JahnTellerAnalyzer.get_analysis_and_structure)


                    * [`JahnTellerAnalyzer.get_magnitude_of_effect_from_species()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.jahnteller.JahnTellerAnalyzer.get_magnitude_of_effect_from_species)


                    * [`JahnTellerAnalyzer.get_magnitude_of_effect_from_spin_config()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.jahnteller.JahnTellerAnalyzer.get_magnitude_of_effect_from_spin_config)


                    * [`JahnTellerAnalyzer.is_jahn_teller_active()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.jahnteller.JahnTellerAnalyzer.is_jahn_teller_active)


                    * [`JahnTellerAnalyzer.mu_so()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.jahnteller.JahnTellerAnalyzer.mu_so)


                    * [`JahnTellerAnalyzer.tag_structure()`](pymatgen.analysis.magnetism.md#pymatgen.analysis.magnetism.jahnteller.JahnTellerAnalyzer.tag_structure)


        * [pymatgen.analysis.solar package](pymatgen.analysis.solar.md)




            * [pymatgen.analysis.solar.slme module](pymatgen.analysis.solar.md#module-pymatgen.analysis.solar.slme)


                * [`absorption_coefficient()`](pymatgen.analysis.solar.md#pymatgen.analysis.solar.slme.absorption_coefficient)


                * [`get_dir_indir_gap()`](pymatgen.analysis.solar.md#pymatgen.analysis.solar.slme.get_dir_indir_gap)


                * [`optics()`](pymatgen.analysis.solar.md#pymatgen.analysis.solar.slme.optics)


                * [`parse_dielectric_data()`](pymatgen.analysis.solar.md#pymatgen.analysis.solar.slme.parse_dielectric_data)


                * [`slme()`](pymatgen.analysis.solar.md#pymatgen.analysis.solar.slme.slme)


                * [`to_matrix()`](pymatgen.analysis.solar.md#pymatgen.analysis.solar.slme.to_matrix)


        * [pymatgen.analysis.structure_prediction package](pymatgen.analysis.structure_prediction.md)




            * [pymatgen.analysis.structure_prediction.dopant_predictor module](pymatgen.analysis.structure_prediction.md#module-pymatgen.analysis.structure_prediction.dopant_predictor)


                * [`_get_dopants()`](pymatgen.analysis.structure_prediction.md#pymatgen.analysis.structure_prediction.dopant_predictor._get_dopants)


                * [`_int_to_roman()`](pymatgen.analysis.structure_prediction.md#pymatgen.analysis.structure_prediction.dopant_predictor._int_to_roman)


                * [`_shannon_radii_from_cn()`](pymatgen.analysis.structure_prediction.md#pymatgen.analysis.structure_prediction.dopant_predictor._shannon_radii_from_cn)


                * [`get_dopants_from_shannon_radii()`](pymatgen.analysis.structure_prediction.md#pymatgen.analysis.structure_prediction.dopant_predictor.get_dopants_from_shannon_radii)


                * [`get_dopants_from_substitution_probabilities()`](pymatgen.analysis.structure_prediction.md#pymatgen.analysis.structure_prediction.dopant_predictor.get_dopants_from_substitution_probabilities)


            * [pymatgen.analysis.structure_prediction.substitution_probability module](pymatgen.analysis.structure_prediction.md#module-pymatgen.analysis.structure_prediction.substitution_probability)


                * [`SubstitutionPredictor`](pymatgen.analysis.structure_prediction.md#pymatgen.analysis.structure_prediction.substitution_probability.SubstitutionPredictor)


                    * [`SubstitutionPredictor.composition_prediction()`](pymatgen.analysis.structure_prediction.md#pymatgen.analysis.structure_prediction.substitution_probability.SubstitutionPredictor.composition_prediction)


                    * [`SubstitutionPredictor.list_prediction()`](pymatgen.analysis.structure_prediction.md#pymatgen.analysis.structure_prediction.substitution_probability.SubstitutionPredictor.list_prediction)


                * [`SubstitutionProbability`](pymatgen.analysis.structure_prediction.md#pymatgen.analysis.structure_prediction.substitution_probability.SubstitutionProbability)


            * [pymatgen.analysis.structure_prediction.substitutor module](pymatgen.analysis.structure_prediction.md#module-pymatgen.analysis.structure_prediction.substitutor)


                * [`Substitutor`](pymatgen.analysis.structure_prediction.md#pymatgen.analysis.structure_prediction.substitutor.Substitutor)


                    * [`Substitutor._is_charge_balanced()`](pymatgen.analysis.structure_prediction.md#pymatgen.analysis.structure_prediction.substitutor.Substitutor._is_charge_balanced)


                    * [`Substitutor._is_from_chemical_system()`](pymatgen.analysis.structure_prediction.md#pymatgen.analysis.structure_prediction.substitutor.Substitutor._is_from_chemical_system)


                    * [`Substitutor.as_dict()`](pymatgen.analysis.structure_prediction.md#pymatgen.analysis.structure_prediction.substitutor.Substitutor.as_dict)


                    * [`Substitutor.from_dict()`](pymatgen.analysis.structure_prediction.md#pymatgen.analysis.structure_prediction.substitutor.Substitutor.from_dict)


                    * [`Substitutor.get_allowed_species()`](pymatgen.analysis.structure_prediction.md#pymatgen.analysis.structure_prediction.substitutor.Substitutor.get_allowed_species)


                    * [`Substitutor.pred_from_comp()`](pymatgen.analysis.structure_prediction.md#pymatgen.analysis.structure_prediction.substitutor.Substitutor.pred_from_comp)


                    * [`Substitutor.pred_from_list()`](pymatgen.analysis.structure_prediction.md#pymatgen.analysis.structure_prediction.substitutor.Substitutor.pred_from_list)


                    * [`Substitutor.pred_from_structures()`](pymatgen.analysis.structure_prediction.md#pymatgen.analysis.structure_prediction.substitutor.Substitutor.pred_from_structures)


            * [pymatgen.analysis.structure_prediction.volume_predictor module](pymatgen.analysis.structure_prediction.md#module-pymatgen.analysis.structure_prediction.volume_predictor)


                * [`DLSVolumePredictor`](pymatgen.analysis.structure_prediction.md#pymatgen.analysis.structure_prediction.volume_predictor.DLSVolumePredictor)


                    * [`DLSVolumePredictor.get_predicted_structure()`](pymatgen.analysis.structure_prediction.md#pymatgen.analysis.structure_prediction.volume_predictor.DLSVolumePredictor.get_predicted_structure)


                    * [`DLSVolumePredictor.predict()`](pymatgen.analysis.structure_prediction.md#pymatgen.analysis.structure_prediction.volume_predictor.DLSVolumePredictor.predict)


                * [`RLSVolumePredictor`](pymatgen.analysis.structure_prediction.md#pymatgen.analysis.structure_prediction.volume_predictor.RLSVolumePredictor)


                    * [`RLSVolumePredictor.get_predicted_structure()`](pymatgen.analysis.structure_prediction.md#pymatgen.analysis.structure_prediction.volume_predictor.RLSVolumePredictor.get_predicted_structure)


                    * [`RLSVolumePredictor.predict()`](pymatgen.analysis.structure_prediction.md#pymatgen.analysis.structure_prediction.volume_predictor.RLSVolumePredictor.predict)


                * [`_is_ox()`](pymatgen.analysis.structure_prediction.md#pymatgen.analysis.structure_prediction.volume_predictor._is_ox)


        * [pymatgen.analysis.topological package](pymatgen.analysis.topological.md)




            * [pymatgen.analysis.topological.spillage module](pymatgen.analysis.topological.md#module-pymatgen.analysis.topological.spillage)


                * [`SOCSpillage`](pymatgen.analysis.topological.md#pymatgen.analysis.topological.spillage.SOCSpillage)


                    * [`SOCSpillage.isclose()`](pymatgen.analysis.topological.md#pymatgen.analysis.topological.spillage.SOCSpillage.isclose)


                    * [`SOCSpillage.orth()`](pymatgen.analysis.topological.md#pymatgen.analysis.topological.spillage.SOCSpillage.orth)


                    * [`SOCSpillage.overlap_so_spinpol()`](pymatgen.analysis.topological.md#pymatgen.analysis.topological.spillage.SOCSpillage.overlap_so_spinpol)


        * [pymatgen.analysis.xas package](pymatgen.analysis.xas.md)




            * [pymatgen.analysis.xas.spectrum module](pymatgen.analysis.xas.md#module-pymatgen.analysis.xas.spectrum)


                * [`XAS`](pymatgen.analysis.xas.md#pymatgen.analysis.xas.spectrum.XAS)


                    * [`XAS.x`](pymatgen.analysis.xas.md#pymatgen.analysis.xas.spectrum.XAS.x)


                    * [`XAS.y`](pymatgen.analysis.xas.md#pymatgen.analysis.xas.spectrum.XAS.y)


                    * [`XAS.absorbing_element`](pymatgen.analysis.xas.md#pymatgen.analysis.xas.spectrum.XAS.absorbing_element)


                    * [`XAS.edge`](pymatgen.analysis.xas.md#pymatgen.analysis.xas.spectrum.XAS.edge)


                    * [`XAS.spectrum_type`](pymatgen.analysis.xas.md#pymatgen.analysis.xas.spectrum.XAS.spectrum_type)


                    * [`XAS.absorbing_index`](pymatgen.analysis.xas.md#pymatgen.analysis.xas.spectrum.XAS.absorbing_index)


                    * [`XAS.XLABEL`](pymatgen.analysis.xas.md#pymatgen.analysis.xas.spectrum.XAS.XLABEL)


                    * [`XAS.YLABEL`](pymatgen.analysis.xas.md#pymatgen.analysis.xas.spectrum.XAS.YLABEL)


                    * [`XAS.stitch()`](pymatgen.analysis.xas.md#pymatgen.analysis.xas.spectrum.XAS.stitch)


                * [`site_weighted_spectrum()`](pymatgen.analysis.xas.md#pymatgen.analysis.xas.spectrum.site_weighted_spectrum)




    * [pymatgen.analysis.adsorption module](pymatgen.analysis.md#module-pymatgen.analysis.adsorption)


        * [`AdsorbateSiteFinder`](pymatgen.analysis.md#pymatgen.analysis.adsorption.AdsorbateSiteFinder)


            * [`AdsorbateSiteFinder.add_adsorbate()`](pymatgen.analysis.md#pymatgen.analysis.adsorption.AdsorbateSiteFinder.add_adsorbate)


            * [`AdsorbateSiteFinder.adsorb_both_surfaces()`](pymatgen.analysis.md#pymatgen.analysis.adsorption.AdsorbateSiteFinder.adsorb_both_surfaces)


            * [`AdsorbateSiteFinder.assign_selective_dynamics()`](pymatgen.analysis.md#pymatgen.analysis.adsorption.AdsorbateSiteFinder.assign_selective_dynamics)


            * [`AdsorbateSiteFinder.assign_site_properties()`](pymatgen.analysis.md#pymatgen.analysis.adsorption.AdsorbateSiteFinder.assign_site_properties)


            * [`AdsorbateSiteFinder.ensemble_center()`](pymatgen.analysis.md#pymatgen.analysis.adsorption.AdsorbateSiteFinder.ensemble_center)


            * [`AdsorbateSiteFinder.find_adsorption_sites()`](pymatgen.analysis.md#pymatgen.analysis.adsorption.AdsorbateSiteFinder.find_adsorption_sites)


            * [`AdsorbateSiteFinder.find_surface_sites_by_height()`](pymatgen.analysis.md#pymatgen.analysis.adsorption.AdsorbateSiteFinder.find_surface_sites_by_height)


            * [`AdsorbateSiteFinder.from_bulk_and_miller()`](pymatgen.analysis.md#pymatgen.analysis.adsorption.AdsorbateSiteFinder.from_bulk_and_miller)


            * [`AdsorbateSiteFinder.generate_adsorption_structures()`](pymatgen.analysis.md#pymatgen.analysis.adsorption.AdsorbateSiteFinder.generate_adsorption_structures)


            * [`AdsorbateSiteFinder.generate_substitution_structures()`](pymatgen.analysis.md#pymatgen.analysis.adsorption.AdsorbateSiteFinder.generate_substitution_structures)


            * [`AdsorbateSiteFinder.get_extended_surface_mesh()`](pymatgen.analysis.md#pymatgen.analysis.adsorption.AdsorbateSiteFinder.get_extended_surface_mesh)


            * [`AdsorbateSiteFinder.near_reduce()`](pymatgen.analysis.md#pymatgen.analysis.adsorption.AdsorbateSiteFinder.near_reduce)


            * [`AdsorbateSiteFinder.subsurface_sites()`](pymatgen.analysis.md#pymatgen.analysis.adsorption.AdsorbateSiteFinder.subsurface_sites)


            * [`AdsorbateSiteFinder.surface_sites`](pymatgen.analysis.md#pymatgen.analysis.adsorption.AdsorbateSiteFinder.surface_sites)


            * [`AdsorbateSiteFinder.symm_reduce()`](pymatgen.analysis.md#pymatgen.analysis.adsorption.AdsorbateSiteFinder.symm_reduce)


        * [`get_mi_vec()`](pymatgen.analysis.md#pymatgen.analysis.adsorption.get_mi_vec)


        * [`get_rot()`](pymatgen.analysis.md#pymatgen.analysis.adsorption.get_rot)


        * [`plot_slab()`](pymatgen.analysis.md#pymatgen.analysis.adsorption.plot_slab)


        * [`put_coord_inside()`](pymatgen.analysis.md#pymatgen.analysis.adsorption.put_coord_inside)


        * [`reorient_z()`](pymatgen.analysis.md#pymatgen.analysis.adsorption.reorient_z)


    * [pymatgen.analysis.bond_dissociation module](pymatgen.analysis.md#module-pymatgen.analysis.bond_dissociation)


        * [`BondDissociationEnergies`](pymatgen.analysis.md#pymatgen.analysis.bond_dissociation.BondDissociationEnergies)


            * [`BondDissociationEnergies.build_new_entry()`](pymatgen.analysis.md#pymatgen.analysis.bond_dissociation.BondDissociationEnergies.build_new_entry)


            * [`BondDissociationEnergies.filter_fragment_entries()`](pymatgen.analysis.md#pymatgen.analysis.bond_dissociation.BondDissociationEnergies.filter_fragment_entries)


            * [`BondDissociationEnergies.fragment_and_process()`](pymatgen.analysis.md#pymatgen.analysis.bond_dissociation.BondDissociationEnergies.fragment_and_process)


            * [`BondDissociationEnergies.search_fragment_entries()`](pymatgen.analysis.md#pymatgen.analysis.bond_dissociation.BondDissociationEnergies.search_fragment_entries)


    * [pymatgen.analysis.bond_valence module](pymatgen.analysis.md#module-pymatgen.analysis.bond_valence)


        * [`BVAnalyzer`](pymatgen.analysis.md#pymatgen.analysis.bond_valence.BVAnalyzer)


            * [`BVAnalyzer.CHARGE_NEUTRALITY_TOLERANCE`](pymatgen.analysis.md#pymatgen.analysis.bond_valence.BVAnalyzer.CHARGE_NEUTRALITY_TOLERANCE)


            * [`BVAnalyzer._calc_site_probabilities()`](pymatgen.analysis.md#pymatgen.analysis.bond_valence.BVAnalyzer._calc_site_probabilities)


            * [`BVAnalyzer._calc_site_probabilities_unordered()`](pymatgen.analysis.md#pymatgen.analysis.bond_valence.BVAnalyzer._calc_site_probabilities_unordered)


            * [`BVAnalyzer.get_oxi_state_decorated_structure()`](pymatgen.analysis.md#pymatgen.analysis.bond_valence.BVAnalyzer.get_oxi_state_decorated_structure)


            * [`BVAnalyzer.get_valences()`](pymatgen.analysis.md#pymatgen.analysis.bond_valence.BVAnalyzer.get_valences)


        * [`add_oxidation_state_by_site_fraction()`](pymatgen.analysis.md#pymatgen.analysis.bond_valence.add_oxidation_state_by_site_fraction)


        * [`calculate_bv_sum()`](pymatgen.analysis.md#pymatgen.analysis.bond_valence.calculate_bv_sum)


        * [`calculate_bv_sum_unordered()`](pymatgen.analysis.md#pymatgen.analysis.bond_valence.calculate_bv_sum_unordered)


        * [`get_z_ordered_elmap()`](pymatgen.analysis.md#pymatgen.analysis.bond_valence.get_z_ordered_elmap)


    * [pymatgen.analysis.chempot_diagram module](pymatgen.analysis.md#module-pymatgen.analysis.chempot_diagram)


        * [`ChemicalPotentialDiagram`](pymatgen.analysis.md#pymatgen.analysis.chempot_diagram.ChemicalPotentialDiagram)


            * [`ChemicalPotentialDiagram._get_2d_domain_lines()`](pymatgen.analysis.md#pymatgen.analysis.chempot_diagram.ChemicalPotentialDiagram._get_2d_domain_lines)


            * [`ChemicalPotentialDiagram._get_2d_plot()`](pymatgen.analysis.md#pymatgen.analysis.chempot_diagram.ChemicalPotentialDiagram._get_2d_plot)


            * [`ChemicalPotentialDiagram._get_3d_domain_lines()`](pymatgen.analysis.md#pymatgen.analysis.chempot_diagram.ChemicalPotentialDiagram._get_3d_domain_lines)


            * [`ChemicalPotentialDiagram._get_3d_domain_simplexes_and_ann_loc()`](pymatgen.analysis.md#pymatgen.analysis.chempot_diagram.ChemicalPotentialDiagram._get_3d_domain_simplexes_and_ann_loc)


            * [`ChemicalPotentialDiagram._get_3d_formula_lines()`](pymatgen.analysis.md#pymatgen.analysis.chempot_diagram.ChemicalPotentialDiagram._get_3d_formula_lines)


            * [`ChemicalPotentialDiagram._get_3d_formula_meshes()`](pymatgen.analysis.md#pymatgen.analysis.chempot_diagram.ChemicalPotentialDiagram._get_3d_formula_meshes)


            * [`ChemicalPotentialDiagram._get_3d_plot()`](pymatgen.analysis.md#pymatgen.analysis.chempot_diagram.ChemicalPotentialDiagram._get_3d_plot)


            * [`ChemicalPotentialDiagram._get_annotation()`](pymatgen.analysis.md#pymatgen.analysis.chempot_diagram.ChemicalPotentialDiagram._get_annotation)


            * [`ChemicalPotentialDiagram._get_axis_layout_dict()`](pymatgen.analysis.md#pymatgen.analysis.chempot_diagram.ChemicalPotentialDiagram._get_axis_layout_dict)


            * [`ChemicalPotentialDiagram._get_border_hyperplanes()`](pymatgen.analysis.md#pymatgen.analysis.chempot_diagram.ChemicalPotentialDiagram._get_border_hyperplanes)


            * [`ChemicalPotentialDiagram._get_domains()`](pymatgen.analysis.md#pymatgen.analysis.chempot_diagram.ChemicalPotentialDiagram._get_domains)


            * [`ChemicalPotentialDiagram._get_hyperplanes_and_entries()`](pymatgen.analysis.md#pymatgen.analysis.chempot_diagram.ChemicalPotentialDiagram._get_hyperplanes_and_entries)


            * [`ChemicalPotentialDiagram._get_min_entries_and_el_refs()`](pymatgen.analysis.md#pymatgen.analysis.chempot_diagram.ChemicalPotentialDiagram._get_min_entries_and_el_refs)


            * [`ChemicalPotentialDiagram._get_new_limits_from_padding()`](pymatgen.analysis.md#pymatgen.analysis.chempot_diagram.ChemicalPotentialDiagram._get_new_limits_from_padding)


            * [`ChemicalPotentialDiagram.border_hyperplanes`](pymatgen.analysis.md#pymatgen.analysis.chempot_diagram.ChemicalPotentialDiagram.border_hyperplanes)


            * [`ChemicalPotentialDiagram.chemical_system`](pymatgen.analysis.md#pymatgen.analysis.chempot_diagram.ChemicalPotentialDiagram.chemical_system)


            * [`ChemicalPotentialDiagram.domains`](pymatgen.analysis.md#pymatgen.analysis.chempot_diagram.ChemicalPotentialDiagram.domains)


            * [`ChemicalPotentialDiagram.el_refs`](pymatgen.analysis.md#pymatgen.analysis.chempot_diagram.ChemicalPotentialDiagram.el_refs)


            * [`ChemicalPotentialDiagram.entry_dict`](pymatgen.analysis.md#pymatgen.analysis.chempot_diagram.ChemicalPotentialDiagram.entry_dict)


            * [`ChemicalPotentialDiagram.get_plot()`](pymatgen.analysis.md#pymatgen.analysis.chempot_diagram.ChemicalPotentialDiagram.get_plot)


            * [`ChemicalPotentialDiagram.hyperplane_entries`](pymatgen.analysis.md#pymatgen.analysis.chempot_diagram.ChemicalPotentialDiagram.hyperplane_entries)


            * [`ChemicalPotentialDiagram.hyperplanes`](pymatgen.analysis.md#pymatgen.analysis.chempot_diagram.ChemicalPotentialDiagram.hyperplanes)


            * [`ChemicalPotentialDiagram.lims`](pymatgen.analysis.md#pymatgen.analysis.chempot_diagram.ChemicalPotentialDiagram.lims)


        * [`_renormalize_entry()`](pymatgen.analysis.md#pymatgen.analysis.chempot_diagram._renormalize_entry)


        * [`get_2d_orthonormal_vector()`](pymatgen.analysis.md#pymatgen.analysis.chempot_diagram.get_2d_orthonormal_vector)


        * [`get_centroid_2d()`](pymatgen.analysis.md#pymatgen.analysis.chempot_diagram.get_centroid_2d)


        * [`simple_pca()`](pymatgen.analysis.md#pymatgen.analysis.chempot_diagram.simple_pca)


    * [pymatgen.analysis.cost module](pymatgen.analysis.md#module-pymatgen.analysis.cost)


        * [`CostAnalyzer`](pymatgen.analysis.md#pymatgen.analysis.cost.CostAnalyzer)


            * [`CostAnalyzer.get_cost_per_kg()`](pymatgen.analysis.md#pymatgen.analysis.cost.CostAnalyzer.get_cost_per_kg)


            * [`CostAnalyzer.get_cost_per_mol()`](pymatgen.analysis.md#pymatgen.analysis.cost.CostAnalyzer.get_cost_per_mol)


            * [`CostAnalyzer.get_lowest_decomposition()`](pymatgen.analysis.md#pymatgen.analysis.cost.CostAnalyzer.get_lowest_decomposition)


        * [`CostDB`](pymatgen.analysis.md#pymatgen.analysis.cost.CostDB)


            * [`CostDB._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.cost.CostDB._abc_impl)


            * [`CostDB.get_entries()`](pymatgen.analysis.md#pymatgen.analysis.cost.CostDB.get_entries)


        * [`CostDBCSV`](pymatgen.analysis.md#pymatgen.analysis.cost.CostDBCSV)


            * [`CostDBCSV._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.cost.CostDBCSV._abc_impl)


            * [`CostDBCSV.get_entries()`](pymatgen.analysis.md#pymatgen.analysis.cost.CostDBCSV.get_entries)


        * [`CostEntry`](pymatgen.analysis.md#pymatgen.analysis.cost.CostEntry)


            * [`CostEntry._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.cost.CostEntry._abc_impl)


    * [pymatgen.analysis.dimensionality module](pymatgen.analysis.md#module-pymatgen.analysis.dimensionality)


        * [`calculate_dimensionality_of_site()`](pymatgen.analysis.md#pymatgen.analysis.dimensionality.calculate_dimensionality_of_site)


        * [`find_clusters()`](pymatgen.analysis.md#pymatgen.analysis.dimensionality.find_clusters)


        * [`find_connected_atoms()`](pymatgen.analysis.md#pymatgen.analysis.dimensionality.find_connected_atoms)


        * [`get_dimensionality_cheon()`](pymatgen.analysis.md#pymatgen.analysis.dimensionality.get_dimensionality_cheon)


        * [`get_dimensionality_gorai()`](pymatgen.analysis.md#pymatgen.analysis.dimensionality.get_dimensionality_gorai)


        * [`get_dimensionality_larsen()`](pymatgen.analysis.md#pymatgen.analysis.dimensionality.get_dimensionality_larsen)


        * [`get_structure_components()`](pymatgen.analysis.md#pymatgen.analysis.dimensionality.get_structure_components)


        * [`zero_d_graph_to_molecule_graph()`](pymatgen.analysis.md#pymatgen.analysis.dimensionality.zero_d_graph_to_molecule_graph)


    * [pymatgen.analysis.disorder module](pymatgen.analysis.md#module-pymatgen.analysis.disorder)


        * [`get_warren_cowley_parameters()`](pymatgen.analysis.md#pymatgen.analysis.disorder.get_warren_cowley_parameters)


    * [pymatgen.analysis.energy_models module](pymatgen.analysis.md#module-pymatgen.analysis.energy_models)


        * [`EnergyModel`](pymatgen.analysis.md#pymatgen.analysis.energy_models.EnergyModel)


            * [`EnergyModel._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.energy_models.EnergyModel._abc_impl)


            * [`EnergyModel.from_dict()`](pymatgen.analysis.md#pymatgen.analysis.energy_models.EnergyModel.from_dict)


            * [`EnergyModel.get_energy()`](pymatgen.analysis.md#pymatgen.analysis.energy_models.EnergyModel.get_energy)


        * [`EwaldElectrostaticModel`](pymatgen.analysis.md#pymatgen.analysis.energy_models.EwaldElectrostaticModel)


            * [`EwaldElectrostaticModel._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.energy_models.EwaldElectrostaticModel._abc_impl)


            * [`EwaldElectrostaticModel.as_dict()`](pymatgen.analysis.md#pymatgen.analysis.energy_models.EwaldElectrostaticModel.as_dict)


            * [`EwaldElectrostaticModel.get_energy()`](pymatgen.analysis.md#pymatgen.analysis.energy_models.EwaldElectrostaticModel.get_energy)


        * [`IsingModel`](pymatgen.analysis.md#pymatgen.analysis.energy_models.IsingModel)


            * [`IsingModel._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.energy_models.IsingModel._abc_impl)


            * [`IsingModel.as_dict()`](pymatgen.analysis.md#pymatgen.analysis.energy_models.IsingModel.as_dict)


            * [`IsingModel.get_energy()`](pymatgen.analysis.md#pymatgen.analysis.energy_models.IsingModel.get_energy)


        * [`NsitesModel`](pymatgen.analysis.md#pymatgen.analysis.energy_models.NsitesModel)


            * [`NsitesModel._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.energy_models.NsitesModel._abc_impl)


            * [`NsitesModel.as_dict()`](pymatgen.analysis.md#pymatgen.analysis.energy_models.NsitesModel.as_dict)


            * [`NsitesModel.get_energy()`](pymatgen.analysis.md#pymatgen.analysis.energy_models.NsitesModel.get_energy)


        * [`SymmetryModel`](pymatgen.analysis.md#pymatgen.analysis.energy_models.SymmetryModel)


            * [`SymmetryModel._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.energy_models.SymmetryModel._abc_impl)


            * [`SymmetryModel.as_dict()`](pymatgen.analysis.md#pymatgen.analysis.energy_models.SymmetryModel.as_dict)


            * [`SymmetryModel.get_energy()`](pymatgen.analysis.md#pymatgen.analysis.energy_models.SymmetryModel.get_energy)


    * [pymatgen.analysis.eos module](pymatgen.analysis.md#module-pymatgen.analysis.eos)


        * [`Birch`](pymatgen.analysis.md#pymatgen.analysis.eos.Birch)


            * [`Birch._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.eos.Birch._abc_impl)


            * [`Birch._func()`](pymatgen.analysis.md#pymatgen.analysis.eos.Birch._func)


        * [`BirchMurnaghan`](pymatgen.analysis.md#pymatgen.analysis.eos.BirchMurnaghan)


            * [`BirchMurnaghan._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.eos.BirchMurnaghan._abc_impl)


            * [`BirchMurnaghan._func()`](pymatgen.analysis.md#pymatgen.analysis.eos.BirchMurnaghan._func)


        * [`DeltaFactor`](pymatgen.analysis.md#pymatgen.analysis.eos.DeltaFactor)


            * [`DeltaFactor._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.eos.DeltaFactor._abc_impl)


            * [`DeltaFactor._func()`](pymatgen.analysis.md#pymatgen.analysis.eos.DeltaFactor._func)


            * [`DeltaFactor._set_params()`](pymatgen.analysis.md#pymatgen.analysis.eos.DeltaFactor._set_params)


            * [`DeltaFactor.fit()`](pymatgen.analysis.md#pymatgen.analysis.eos.DeltaFactor.fit)


        * [`EOS`](pymatgen.analysis.md#pymatgen.analysis.eos.EOS)


            * [`EOS.MODELS`](pymatgen.analysis.md#pymatgen.analysis.eos.EOS.MODELS)


            * [`EOS.fit()`](pymatgen.analysis.md#pymatgen.analysis.eos.EOS.fit)


        * [`EOSBase`](pymatgen.analysis.md#pymatgen.analysis.eos.EOSBase)


            * [`EOSBase._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.eos.EOSBase._abc_impl)


            * [`EOSBase._func()`](pymatgen.analysis.md#pymatgen.analysis.eos.EOSBase._func)


            * [`EOSBase._initial_guess()`](pymatgen.analysis.md#pymatgen.analysis.eos.EOSBase._initial_guess)


            * [`EOSBase.b0`](pymatgen.analysis.md#pymatgen.analysis.eos.EOSBase.b0)


            * [`EOSBase.b0_GPa`](pymatgen.analysis.md#pymatgen.analysis.eos.EOSBase.b0_GPa)


            * [`EOSBase.b1`](pymatgen.analysis.md#pymatgen.analysis.eos.EOSBase.b1)


            * [`EOSBase.e0`](pymatgen.analysis.md#pymatgen.analysis.eos.EOSBase.e0)


            * [`EOSBase.fit()`](pymatgen.analysis.md#pymatgen.analysis.eos.EOSBase.fit)


            * [`EOSBase.func()`](pymatgen.analysis.md#pymatgen.analysis.eos.EOSBase.func)


            * [`EOSBase.plot()`](pymatgen.analysis.md#pymatgen.analysis.eos.EOSBase.plot)


            * [`EOSBase.plot_ax()`](pymatgen.analysis.md#pymatgen.analysis.eos.EOSBase.plot_ax)


            * [`EOSBase.results`](pymatgen.analysis.md#pymatgen.analysis.eos.EOSBase.results)


            * [`EOSBase.v0`](pymatgen.analysis.md#pymatgen.analysis.eos.EOSBase.v0)


        * [`EOSError`](pymatgen.analysis.md#pymatgen.analysis.eos.EOSError)


        * [`Murnaghan`](pymatgen.analysis.md#pymatgen.analysis.eos.Murnaghan)


            * [`Murnaghan._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.eos.Murnaghan._abc_impl)


            * [`Murnaghan._func()`](pymatgen.analysis.md#pymatgen.analysis.eos.Murnaghan._func)


        * [`NumericalEOS`](pymatgen.analysis.md#pymatgen.analysis.eos.NumericalEOS)


            * [`NumericalEOS._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.eos.NumericalEOS._abc_impl)


            * [`NumericalEOS.fit()`](pymatgen.analysis.md#pymatgen.analysis.eos.NumericalEOS.fit)


        * [`PolynomialEOS`](pymatgen.analysis.md#pymatgen.analysis.eos.PolynomialEOS)


            * [`PolynomialEOS._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.eos.PolynomialEOS._abc_impl)


            * [`PolynomialEOS._func()`](pymatgen.analysis.md#pymatgen.analysis.eos.PolynomialEOS._func)


            * [`PolynomialEOS._set_params()`](pymatgen.analysis.md#pymatgen.analysis.eos.PolynomialEOS._set_params)


            * [`PolynomialEOS.fit()`](pymatgen.analysis.md#pymatgen.analysis.eos.PolynomialEOS.fit)


        * [`PourierTarantola`](pymatgen.analysis.md#pymatgen.analysis.eos.PourierTarantola)


            * [`PourierTarantola._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.eos.PourierTarantola._abc_impl)


            * [`PourierTarantola._func()`](pymatgen.analysis.md#pymatgen.analysis.eos.PourierTarantola._func)


        * [`Vinet`](pymatgen.analysis.md#pymatgen.analysis.eos.Vinet)


            * [`Vinet._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.eos.Vinet._abc_impl)


            * [`Vinet._func()`](pymatgen.analysis.md#pymatgen.analysis.eos.Vinet._func)


    * [pymatgen.analysis.ewald module](pymatgen.analysis.md#module-pymatgen.analysis.ewald)


        * [`EwaldMinimizer`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldMinimizer)


            * [`EwaldMinimizer.ALGO_BEST_FIRST`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldMinimizer.ALGO_BEST_FIRST)


            * [`EwaldMinimizer.ALGO_COMPLETE`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldMinimizer.ALGO_COMPLETE)


            * [`EwaldMinimizer.ALGO_FAST`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldMinimizer.ALGO_FAST)


            * [`EwaldMinimizer.ALGO_TIME_LIMIT`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldMinimizer.ALGO_TIME_LIMIT)


            * [`EwaldMinimizer._recurse()`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldMinimizer._recurse)


            * [`EwaldMinimizer.add_m_list()`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldMinimizer.add_m_list)


            * [`EwaldMinimizer.best_case()`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldMinimizer.best_case)


            * [`EwaldMinimizer.best_m_list`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldMinimizer.best_m_list)


            * [`EwaldMinimizer.get_next_index()`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldMinimizer.get_next_index)


            * [`EwaldMinimizer.minimize_matrix()`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldMinimizer.minimize_matrix)


            * [`EwaldMinimizer.minimized_sum`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldMinimizer.minimized_sum)


            * [`EwaldMinimizer.output_lists`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldMinimizer.output_lists)


        * [`EwaldSummation`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldSummation)


            * [`EwaldSummation.CONV_FACT`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldSummation.CONV_FACT)


            * [`EwaldSummation._calc_ewald_terms()`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldSummation._calc_ewald_terms)


            * [`EwaldSummation._calc_real_and_point()`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldSummation._calc_real_and_point)


            * [`EwaldSummation._calc_recip()`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldSummation._calc_recip)


            * [`EwaldSummation.as_dict()`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldSummation.as_dict)


            * [`EwaldSummation.compute_partial_energy()`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldSummation.compute_partial_energy)


            * [`EwaldSummation.compute_sub_structure()`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldSummation.compute_sub_structure)


            * [`EwaldSummation.eta`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldSummation.eta)


            * [`EwaldSummation.forces`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldSummation.forces)


            * [`EwaldSummation.from_dict()`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldSummation.from_dict)


            * [`EwaldSummation.get_site_energy()`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldSummation.get_site_energy)


            * [`EwaldSummation.point_energy`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldSummation.point_energy)


            * [`EwaldSummation.point_energy_matrix`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldSummation.point_energy_matrix)


            * [`EwaldSummation.real_space_energy`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldSummation.real_space_energy)


            * [`EwaldSummation.real_space_energy_matrix`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldSummation.real_space_energy_matrix)


            * [`EwaldSummation.reciprocal_space_energy`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldSummation.reciprocal_space_energy)


            * [`EwaldSummation.reciprocal_space_energy_matrix`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldSummation.reciprocal_space_energy_matrix)


            * [`EwaldSummation.total_energy`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldSummation.total_energy)


            * [`EwaldSummation.total_energy_matrix`](pymatgen.analysis.md#pymatgen.analysis.ewald.EwaldSummation.total_energy_matrix)


        * [`compute_average_oxidation_state()`](pymatgen.analysis.md#pymatgen.analysis.ewald.compute_average_oxidation_state)


    * [pymatgen.analysis.excitation module](pymatgen.analysis.md#module-pymatgen.analysis.excitation)


        * [`ExcitationSpectrum`](pymatgen.analysis.md#pymatgen.analysis.excitation.ExcitationSpectrum)


            * [`ExcitationSpectrum.x`](pymatgen.analysis.md#pymatgen.analysis.excitation.ExcitationSpectrum.x)


            * [`ExcitationSpectrum.y`](pymatgen.analysis.md#pymatgen.analysis.excitation.ExcitationSpectrum.y)


            * [`ExcitationSpectrum.XLABEL`](pymatgen.analysis.md#pymatgen.analysis.excitation.ExcitationSpectrum.XLABEL)


            * [`ExcitationSpectrum.YLABEL`](pymatgen.analysis.md#pymatgen.analysis.excitation.ExcitationSpectrum.YLABEL)


    * [pymatgen.analysis.fragmenter module](pymatgen.analysis.md#module-pymatgen.analysis.fragmenter)


        * [`Fragmenter`](pymatgen.analysis.md#pymatgen.analysis.fragmenter.Fragmenter)


            * [`Fragmenter._fragment_one_level()`](pymatgen.analysis.md#pymatgen.analysis.fragmenter.Fragmenter._fragment_one_level)


            * [`Fragmenter._open_all_rings()`](pymatgen.analysis.md#pymatgen.analysis.fragmenter.Fragmenter._open_all_rings)


        * [`open_ring()`](pymatgen.analysis.md#pymatgen.analysis.fragmenter.open_ring)


    * [pymatgen.analysis.functional_groups module](pymatgen.analysis.md#module-pymatgen.analysis.functional_groups)


        * [`FunctionalGroupExtractor`](pymatgen.analysis.md#pymatgen.analysis.functional_groups.FunctionalGroupExtractor)


            * [`FunctionalGroupExtractor.categorize_functional_groups()`](pymatgen.analysis.md#pymatgen.analysis.functional_groups.FunctionalGroupExtractor.categorize_functional_groups)


            * [`FunctionalGroupExtractor.get_all_functional_groups()`](pymatgen.analysis.md#pymatgen.analysis.functional_groups.FunctionalGroupExtractor.get_all_functional_groups)


            * [`FunctionalGroupExtractor.get_basic_functional_groups()`](pymatgen.analysis.md#pymatgen.analysis.functional_groups.FunctionalGroupExtractor.get_basic_functional_groups)


            * [`FunctionalGroupExtractor.get_heteroatoms()`](pymatgen.analysis.md#pymatgen.analysis.functional_groups.FunctionalGroupExtractor.get_heteroatoms)


            * [`FunctionalGroupExtractor.get_special_carbon()`](pymatgen.analysis.md#pymatgen.analysis.functional_groups.FunctionalGroupExtractor.get_special_carbon)


            * [`FunctionalGroupExtractor.link_marked_atoms()`](pymatgen.analysis.md#pymatgen.analysis.functional_groups.FunctionalGroupExtractor.link_marked_atoms)


    * [pymatgen.analysis.graphs module](pymatgen.analysis.md#module-pymatgen.analysis.graphs)


        * [`ConnectedSite`](pymatgen.analysis.md#pymatgen.analysis.graphs.ConnectedSite)


            * [`ConnectedSite._asdict()`](pymatgen.analysis.md#pymatgen.analysis.graphs.ConnectedSite._asdict)


            * [`ConnectedSite._field_defaults`](pymatgen.analysis.md#pymatgen.analysis.graphs.ConnectedSite._field_defaults)


            * [`ConnectedSite._fields`](pymatgen.analysis.md#pymatgen.analysis.graphs.ConnectedSite._fields)


            * [`ConnectedSite._make()`](pymatgen.analysis.md#pymatgen.analysis.graphs.ConnectedSite._make)


            * [`ConnectedSite._replace()`](pymatgen.analysis.md#pymatgen.analysis.graphs.ConnectedSite._replace)


            * [`ConnectedSite.dist`](pymatgen.analysis.md#pymatgen.analysis.graphs.ConnectedSite.dist)


            * [`ConnectedSite.index`](pymatgen.analysis.md#pymatgen.analysis.graphs.ConnectedSite.index)


            * [`ConnectedSite.jimage`](pymatgen.analysis.md#pymatgen.analysis.graphs.ConnectedSite.jimage)


            * [`ConnectedSite.site`](pymatgen.analysis.md#pymatgen.analysis.graphs.ConnectedSite.site)


            * [`ConnectedSite.weight`](pymatgen.analysis.md#pymatgen.analysis.graphs.ConnectedSite.weight)


        * [`MolGraphSplitError`](pymatgen.analysis.md#pymatgen.analysis.graphs.MolGraphSplitError)


        * [`MoleculeGraph`](pymatgen.analysis.md#pymatgen.analysis.graphs.MoleculeGraph)


            * [`MoleculeGraph._edges_to_string()`](pymatgen.analysis.md#pymatgen.analysis.graphs.MoleculeGraph._edges_to_string)


            * [`MoleculeGraph.add_edge()`](pymatgen.analysis.md#pymatgen.analysis.graphs.MoleculeGraph.add_edge)


            * [`MoleculeGraph.alter_edge()`](pymatgen.analysis.md#pymatgen.analysis.graphs.MoleculeGraph.alter_edge)


            * [`MoleculeGraph.as_dict()`](pymatgen.analysis.md#pymatgen.analysis.graphs.MoleculeGraph.as_dict)


            * [`MoleculeGraph.break_edge()`](pymatgen.analysis.md#pymatgen.analysis.graphs.MoleculeGraph.break_edge)


            * [`MoleculeGraph.build_unique_fragments()`](pymatgen.analysis.md#pymatgen.analysis.graphs.MoleculeGraph.build_unique_fragments)


            * [`MoleculeGraph.diff()`](pymatgen.analysis.md#pymatgen.analysis.graphs.MoleculeGraph.diff)


            * [`MoleculeGraph.draw_graph_to_file()`](pymatgen.analysis.md#pymatgen.analysis.graphs.MoleculeGraph.draw_graph_to_file)


            * [`MoleculeGraph.edge_weight_name`](pymatgen.analysis.md#pymatgen.analysis.graphs.MoleculeGraph.edge_weight_name)


            * [`MoleculeGraph.edge_weight_unit`](pymatgen.analysis.md#pymatgen.analysis.graphs.MoleculeGraph.edge_weight_unit)


            * [`MoleculeGraph.find_rings()`](pymatgen.analysis.md#pymatgen.analysis.graphs.MoleculeGraph.find_rings)


            * [`MoleculeGraph.from_dict()`](pymatgen.analysis.md#pymatgen.analysis.graphs.MoleculeGraph.from_dict)


            * [`MoleculeGraph.get_connected_sites()`](pymatgen.analysis.md#pymatgen.analysis.graphs.MoleculeGraph.get_connected_sites)


            * [`MoleculeGraph.get_coordination_of_site()`](pymatgen.analysis.md#pymatgen.analysis.graphs.MoleculeGraph.get_coordination_of_site)


            * [`MoleculeGraph.get_disconnected_fragments()`](pymatgen.analysis.md#pymatgen.analysis.graphs.MoleculeGraph.get_disconnected_fragments)


            * [`MoleculeGraph.insert_node()`](pymatgen.analysis.md#pymatgen.analysis.graphs.MoleculeGraph.insert_node)


            * [`MoleculeGraph.isomorphic_to()`](pymatgen.analysis.md#pymatgen.analysis.graphs.MoleculeGraph.isomorphic_to)


            * [`MoleculeGraph.name`](pymatgen.analysis.md#pymatgen.analysis.graphs.MoleculeGraph.name)


            * [`MoleculeGraph.remove_nodes()`](pymatgen.analysis.md#pymatgen.analysis.graphs.MoleculeGraph.remove_nodes)


            * [`MoleculeGraph.replace_group()`](pymatgen.analysis.md#pymatgen.analysis.graphs.MoleculeGraph.replace_group)


            * [`MoleculeGraph.set_node_attributes()`](pymatgen.analysis.md#pymatgen.analysis.graphs.MoleculeGraph.set_node_attributes)


            * [`MoleculeGraph.sort()`](pymatgen.analysis.md#pymatgen.analysis.graphs.MoleculeGraph.sort)


            * [`MoleculeGraph.split_molecule_subgraphs()`](pymatgen.analysis.md#pymatgen.analysis.graphs.MoleculeGraph.split_molecule_subgraphs)


            * [`MoleculeGraph.substitute_group()`](pymatgen.analysis.md#pymatgen.analysis.graphs.MoleculeGraph.substitute_group)


            * [`MoleculeGraph.with_edges()`](pymatgen.analysis.md#pymatgen.analysis.graphs.MoleculeGraph.with_edges)


            * [`MoleculeGraph.with_empty_graph()`](pymatgen.analysis.md#pymatgen.analysis.graphs.MoleculeGraph.with_empty_graph)


            * [`MoleculeGraph.with_local_env_strategy()`](pymatgen.analysis.md#pymatgen.analysis.graphs.MoleculeGraph.with_local_env_strategy)


        * [`StructureGraph`](pymatgen.analysis.md#pymatgen.analysis.graphs.StructureGraph)


            * [`StructureGraph._edges_to_string()`](pymatgen.analysis.md#pymatgen.analysis.graphs.StructureGraph._edges_to_string)


            * [`StructureGraph.add_edge()`](pymatgen.analysis.md#pymatgen.analysis.graphs.StructureGraph.add_edge)


            * [`StructureGraph.alter_edge()`](pymatgen.analysis.md#pymatgen.analysis.graphs.StructureGraph.alter_edge)


            * [`StructureGraph.as_dict()`](pymatgen.analysis.md#pymatgen.analysis.graphs.StructureGraph.as_dict)


            * [`StructureGraph.break_edge()`](pymatgen.analysis.md#pymatgen.analysis.graphs.StructureGraph.break_edge)


            * [`StructureGraph.diff()`](pymatgen.analysis.md#pymatgen.analysis.graphs.StructureGraph.diff)


            * [`StructureGraph.draw_graph_to_file()`](pymatgen.analysis.md#pymatgen.analysis.graphs.StructureGraph.draw_graph_to_file)


            * [`StructureGraph.edge_weight_name`](pymatgen.analysis.md#pymatgen.analysis.graphs.StructureGraph.edge_weight_name)


            * [`StructureGraph.edge_weight_unit`](pymatgen.analysis.md#pymatgen.analysis.graphs.StructureGraph.edge_weight_unit)


            * [`StructureGraph.from_dict()`](pymatgen.analysis.md#pymatgen.analysis.graphs.StructureGraph.from_dict)


            * [`StructureGraph.get_connected_sites()`](pymatgen.analysis.md#pymatgen.analysis.graphs.StructureGraph.get_connected_sites)


            * [`StructureGraph.get_coordination_of_site()`](pymatgen.analysis.md#pymatgen.analysis.graphs.StructureGraph.get_coordination_of_site)


            * [`StructureGraph.get_subgraphs_as_molecules()`](pymatgen.analysis.md#pymatgen.analysis.graphs.StructureGraph.get_subgraphs_as_molecules)


            * [`StructureGraph.insert_node()`](pymatgen.analysis.md#pymatgen.analysis.graphs.StructureGraph.insert_node)


            * [`StructureGraph.name`](pymatgen.analysis.md#pymatgen.analysis.graphs.StructureGraph.name)


            * [`StructureGraph.remove_nodes()`](pymatgen.analysis.md#pymatgen.analysis.graphs.StructureGraph.remove_nodes)


            * [`StructureGraph.set_node_attributes()`](pymatgen.analysis.md#pymatgen.analysis.graphs.StructureGraph.set_node_attributes)


            * [`StructureGraph.sort()`](pymatgen.analysis.md#pymatgen.analysis.graphs.StructureGraph.sort)


            * [`StructureGraph.substitute_group()`](pymatgen.analysis.md#pymatgen.analysis.graphs.StructureGraph.substitute_group)


            * [`StructureGraph.types_and_weights_of_connections`](pymatgen.analysis.md#pymatgen.analysis.graphs.StructureGraph.types_and_weights_of_connections)


            * [`StructureGraph.types_of_coordination_environments()`](pymatgen.analysis.md#pymatgen.analysis.graphs.StructureGraph.types_of_coordination_environments)


            * [`StructureGraph.weight_statistics`](pymatgen.analysis.md#pymatgen.analysis.graphs.StructureGraph.weight_statistics)


            * [`StructureGraph.with_edges()`](pymatgen.analysis.md#pymatgen.analysis.graphs.StructureGraph.with_edges)


            * [`StructureGraph.with_empty_graph()`](pymatgen.analysis.md#pymatgen.analysis.graphs.StructureGraph.with_empty_graph)


            * [`StructureGraph.with_local_env_strategy()`](pymatgen.analysis.md#pymatgen.analysis.graphs.StructureGraph.with_local_env_strategy)


        * [`_compare()`](pymatgen.analysis.md#pymatgen.analysis.graphs._compare)


        * [`_igraph_from_nxgraph()`](pymatgen.analysis.md#pymatgen.analysis.graphs._igraph_from_nxgraph)


        * [`_isomorphic()`](pymatgen.analysis.md#pymatgen.analysis.graphs._isomorphic)


    * [pymatgen.analysis.hhi module](pymatgen.analysis.md#module-pymatgen.analysis.hhi)


    * [pymatgen.analysis.interface module](pymatgen.analysis.md#module-pymatgen.analysis.interface)


    * [pymatgen.analysis.interface_reactions module](pymatgen.analysis.md#module-pymatgen.analysis.interface_reactions)


        * [`GrandPotentialInterfacialReactivity`](pymatgen.analysis.md#pymatgen.analysis.interface_reactions.GrandPotentialInterfacialReactivity)


            * [`GrandPotentialInterfacialReactivity._get_grand_potential()`](pymatgen.analysis.md#pymatgen.analysis.interface_reactions.GrandPotentialInterfacialReactivity._get_grand_potential)


            * [`GrandPotentialInterfacialReactivity._get_reactants()`](pymatgen.analysis.md#pymatgen.analysis.interface_reactions.GrandPotentialInterfacialReactivity._get_reactants)


            * [`GrandPotentialInterfacialReactivity.get_no_mixing_energy()`](pymatgen.analysis.md#pymatgen.analysis.interface_reactions.GrandPotentialInterfacialReactivity.get_no_mixing_energy)


        * [`InterfacialReactivity`](pymatgen.analysis.md#pymatgen.analysis.interface_reactions.InterfacialReactivity)


            * [`InterfacialReactivity.EV_TO_KJ_PER_MOL`](pymatgen.analysis.md#pymatgen.analysis.interface_reactions.InterfacialReactivity.EV_TO_KJ_PER_MOL)


            * [`InterfacialReactivity._convert()`](pymatgen.analysis.md#pymatgen.analysis.interface_reactions.InterfacialReactivity._convert)


            * [`InterfacialReactivity._get_elmt_amt_in_rxn()`](pymatgen.analysis.md#pymatgen.analysis.interface_reactions.InterfacialReactivity._get_elmt_amt_in_rxn)


            * [`InterfacialReactivity._get_energy()`](pymatgen.analysis.md#pymatgen.analysis.interface_reactions.InterfacialReactivity._get_energy)


            * [`InterfacialReactivity._get_entry_energy()`](pymatgen.analysis.md#pymatgen.analysis.interface_reactions.InterfacialReactivity._get_entry_energy)


            * [`InterfacialReactivity._get_matplotlib_figure()`](pymatgen.analysis.md#pymatgen.analysis.interface_reactions.InterfacialReactivity._get_matplotlib_figure)


            * [`InterfacialReactivity._get_original_composition_ratio()`](pymatgen.analysis.md#pymatgen.analysis.interface_reactions.InterfacialReactivity._get_original_composition_ratio)


            * [`InterfacialReactivity._get_plotly_annotations()`](pymatgen.analysis.md#pymatgen.analysis.interface_reactions.InterfacialReactivity._get_plotly_annotations)


            * [`InterfacialReactivity._get_plotly_figure()`](pymatgen.analysis.md#pymatgen.analysis.interface_reactions.InterfacialReactivity._get_plotly_figure)


            * [`InterfacialReactivity._get_reactants()`](pymatgen.analysis.md#pymatgen.analysis.interface_reactions.InterfacialReactivity._get_reactants)


            * [`InterfacialReactivity._get_reaction()`](pymatgen.analysis.md#pymatgen.analysis.interface_reactions.InterfacialReactivity._get_reaction)


            * [`InterfacialReactivity._get_xaxis_title()`](pymatgen.analysis.md#pymatgen.analysis.interface_reactions.InterfacialReactivity._get_xaxis_title)


            * [`InterfacialReactivity._reverse_convert()`](pymatgen.analysis.md#pymatgen.analysis.interface_reactions.InterfacialReactivity._reverse_convert)


            * [`InterfacialReactivity.get_chempot_correction()`](pymatgen.analysis.md#pymatgen.analysis.interface_reactions.InterfacialReactivity.get_chempot_correction)


            * [`InterfacialReactivity.get_critical_original_kink_ratio()`](pymatgen.analysis.md#pymatgen.analysis.interface_reactions.InterfacialReactivity.get_critical_original_kink_ratio)


            * [`InterfacialReactivity.get_dataframe()`](pymatgen.analysis.md#pymatgen.analysis.interface_reactions.InterfacialReactivity.get_dataframe)


            * [`InterfacialReactivity.get_kinks()`](pymatgen.analysis.md#pymatgen.analysis.interface_reactions.InterfacialReactivity.get_kinks)


            * [`InterfacialReactivity.labels`](pymatgen.analysis.md#pymatgen.analysis.interface_reactions.InterfacialReactivity.labels)


            * [`InterfacialReactivity.minimum`](pymatgen.analysis.md#pymatgen.analysis.interface_reactions.InterfacialReactivity.minimum)


            * [`InterfacialReactivity.plot()`](pymatgen.analysis.md#pymatgen.analysis.interface_reactions.InterfacialReactivity.plot)


            * [`InterfacialReactivity.products`](pymatgen.analysis.md#pymatgen.analysis.interface_reactions.InterfacialReactivity.products)


    * [pymatgen.analysis.local_env module](pymatgen.analysis.md#module-pymatgen.analysis.local_env)


        * [`BrunnerNN_real`](pymatgen.analysis.md#pymatgen.analysis.local_env.BrunnerNN_real)


            * [`BrunnerNN_real.get_nn_info()`](pymatgen.analysis.md#pymatgen.analysis.local_env.BrunnerNN_real.get_nn_info)


            * [`BrunnerNN_real.molecules_allowed`](pymatgen.analysis.md#pymatgen.analysis.local_env.BrunnerNN_real.molecules_allowed)


            * [`BrunnerNN_real.structures_allowed`](pymatgen.analysis.md#pymatgen.analysis.local_env.BrunnerNN_real.structures_allowed)


        * [`BrunnerNN_reciprocal`](pymatgen.analysis.md#pymatgen.analysis.local_env.BrunnerNN_reciprocal)


            * [`BrunnerNN_reciprocal.get_nn_info()`](pymatgen.analysis.md#pymatgen.analysis.local_env.BrunnerNN_reciprocal.get_nn_info)


            * [`BrunnerNN_reciprocal.molecules_allowed`](pymatgen.analysis.md#pymatgen.analysis.local_env.BrunnerNN_reciprocal.molecules_allowed)


            * [`BrunnerNN_reciprocal.structures_allowed`](pymatgen.analysis.md#pymatgen.analysis.local_env.BrunnerNN_reciprocal.structures_allowed)


        * [`BrunnerNN_relative`](pymatgen.analysis.md#pymatgen.analysis.local_env.BrunnerNN_relative)


            * [`BrunnerNN_relative.get_nn_info()`](pymatgen.analysis.md#pymatgen.analysis.local_env.BrunnerNN_relative.get_nn_info)


            * [`BrunnerNN_relative.molecules_allowed`](pymatgen.analysis.md#pymatgen.analysis.local_env.BrunnerNN_relative.molecules_allowed)


            * [`BrunnerNN_relative.structures_allowed`](pymatgen.analysis.md#pymatgen.analysis.local_env.BrunnerNN_relative.structures_allowed)


        * [`CovalentBondNN`](pymatgen.analysis.md#pymatgen.analysis.local_env.CovalentBondNN)


            * [`CovalentBondNN.extend_structure_molecules`](pymatgen.analysis.md#pymatgen.analysis.local_env.CovalentBondNN.extend_structure_molecules)


            * [`CovalentBondNN.get_bonded_structure()`](pymatgen.analysis.md#pymatgen.analysis.local_env.CovalentBondNN.get_bonded_structure)


            * [`CovalentBondNN.get_nn_info()`](pymatgen.analysis.md#pymatgen.analysis.local_env.CovalentBondNN.get_nn_info)


            * [`CovalentBondNN.get_nn_shell_info()`](pymatgen.analysis.md#pymatgen.analysis.local_env.CovalentBondNN.get_nn_shell_info)


            * [`CovalentBondNN.molecules_allowed`](pymatgen.analysis.md#pymatgen.analysis.local_env.CovalentBondNN.molecules_allowed)


            * [`CovalentBondNN.structures_allowed`](pymatgen.analysis.md#pymatgen.analysis.local_env.CovalentBondNN.structures_allowed)


        * [`Critic2NN`](pymatgen.analysis.md#pymatgen.analysis.local_env.Critic2NN)


            * [`Critic2NN.extend_structure_molecules`](pymatgen.analysis.md#pymatgen.analysis.local_env.Critic2NN.extend_structure_molecules)


            * [`Critic2NN.get_bonded_structure()`](pymatgen.analysis.md#pymatgen.analysis.local_env.Critic2NN.get_bonded_structure)


            * [`Critic2NN.get_nn_info()`](pymatgen.analysis.md#pymatgen.analysis.local_env.Critic2NN.get_nn_info)


            * [`Critic2NN.molecules_allowed`](pymatgen.analysis.md#pymatgen.analysis.local_env.Critic2NN.molecules_allowed)


            * [`Critic2NN.structures_allowed`](pymatgen.analysis.md#pymatgen.analysis.local_env.Critic2NN.structures_allowed)


        * [`CrystalNN`](pymatgen.analysis.md#pymatgen.analysis.local_env.CrystalNN)


            * [`CrystalNN.NNData`](pymatgen.analysis.md#pymatgen.analysis.local_env.CrystalNN.NNData)


                * [`CrystalNN.NNData._asdict()`](pymatgen.analysis.md#pymatgen.analysis.local_env.CrystalNN.NNData._asdict)


                * [`CrystalNN.NNData._field_defaults`](pymatgen.analysis.md#pymatgen.analysis.local_env.CrystalNN.NNData._field_defaults)


                * [`CrystalNN.NNData._fields`](pymatgen.analysis.md#pymatgen.analysis.local_env.CrystalNN.NNData._fields)


                * [`CrystalNN.NNData._make()`](pymatgen.analysis.md#pymatgen.analysis.local_env.CrystalNN.NNData._make)


                * [`CrystalNN.NNData._replace()`](pymatgen.analysis.md#pymatgen.analysis.local_env.CrystalNN.NNData._replace)


                * [`CrystalNN.NNData.all_nninfo`](pymatgen.analysis.md#pymatgen.analysis.local_env.CrystalNN.NNData.all_nninfo)


                * [`CrystalNN.NNData.cn_nninfo`](pymatgen.analysis.md#pymatgen.analysis.local_env.CrystalNN.NNData.cn_nninfo)


                * [`CrystalNN.NNData.cn_weights`](pymatgen.analysis.md#pymatgen.analysis.local_env.CrystalNN.NNData.cn_weights)


            * [`CrystalNN._semicircle_integral()`](pymatgen.analysis.md#pymatgen.analysis.local_env.CrystalNN._semicircle_integral)


            * [`CrystalNN.get_cn()`](pymatgen.analysis.md#pymatgen.analysis.local_env.CrystalNN.get_cn)


            * [`CrystalNN.get_cn_dict()`](pymatgen.analysis.md#pymatgen.analysis.local_env.CrystalNN.get_cn_dict)


            * [`CrystalNN.get_nn_data()`](pymatgen.analysis.md#pymatgen.analysis.local_env.CrystalNN.get_nn_data)


            * [`CrystalNN.get_nn_info()`](pymatgen.analysis.md#pymatgen.analysis.local_env.CrystalNN.get_nn_info)


            * [`CrystalNN.molecules_allowed`](pymatgen.analysis.md#pymatgen.analysis.local_env.CrystalNN.molecules_allowed)


            * [`CrystalNN.structures_allowed`](pymatgen.analysis.md#pymatgen.analysis.local_env.CrystalNN.structures_allowed)


            * [`CrystalNN.transform_to_length()`](pymatgen.analysis.md#pymatgen.analysis.local_env.CrystalNN.transform_to_length)


        * [`CutOffDictNN`](pymatgen.analysis.md#pymatgen.analysis.local_env.CutOffDictNN)


            * [`CutOffDictNN.extend_structure_molecules`](pymatgen.analysis.md#pymatgen.analysis.local_env.CutOffDictNN.extend_structure_molecules)


            * [`CutOffDictNN.from_preset()`](pymatgen.analysis.md#pymatgen.analysis.local_env.CutOffDictNN.from_preset)


            * [`CutOffDictNN.get_nn_info()`](pymatgen.analysis.md#pymatgen.analysis.local_env.CutOffDictNN.get_nn_info)


            * [`CutOffDictNN.molecules_allowed`](pymatgen.analysis.md#pymatgen.analysis.local_env.CutOffDictNN.molecules_allowed)


            * [`CutOffDictNN.structures_allowed`](pymatgen.analysis.md#pymatgen.analysis.local_env.CutOffDictNN.structures_allowed)


        * [`EconNN`](pymatgen.analysis.md#pymatgen.analysis.local_env.EconNN)


            * [`EconNN.extend_structure_molecules`](pymatgen.analysis.md#pymatgen.analysis.local_env.EconNN.extend_structure_molecules)


            * [`EconNN.get_nn_info()`](pymatgen.analysis.md#pymatgen.analysis.local_env.EconNN.get_nn_info)


            * [`EconNN.molecules_allowed`](pymatgen.analysis.md#pymatgen.analysis.local_env.EconNN.molecules_allowed)


            * [`EconNN.structures_allowed`](pymatgen.analysis.md#pymatgen.analysis.local_env.EconNN.structures_allowed)


        * [`IsayevNN`](pymatgen.analysis.md#pymatgen.analysis.local_env.IsayevNN)


            * [`IsayevNN._filter_nns()`](pymatgen.analysis.md#pymatgen.analysis.local_env.IsayevNN._filter_nns)


            * [`IsayevNN.get_all_nn_info()`](pymatgen.analysis.md#pymatgen.analysis.local_env.IsayevNN.get_all_nn_info)


            * [`IsayevNN.get_nn_info()`](pymatgen.analysis.md#pymatgen.analysis.local_env.IsayevNN.get_nn_info)


        * [`JmolNN`](pymatgen.analysis.md#pymatgen.analysis.local_env.JmolNN)


            * [`JmolNN.extend_structure_molecules`](pymatgen.analysis.md#pymatgen.analysis.local_env.JmolNN.extend_structure_molecules)


            * [`JmolNN.get_max_bond_distance()`](pymatgen.analysis.md#pymatgen.analysis.local_env.JmolNN.get_max_bond_distance)


            * [`JmolNN.get_nn_info()`](pymatgen.analysis.md#pymatgen.analysis.local_env.JmolNN.get_nn_info)


            * [`JmolNN.molecules_allowed`](pymatgen.analysis.md#pymatgen.analysis.local_env.JmolNN.molecules_allowed)


            * [`JmolNN.structures_allowed`](pymatgen.analysis.md#pymatgen.analysis.local_env.JmolNN.structures_allowed)


        * [`LocalStructOrderParams`](pymatgen.analysis.md#pymatgen.analysis.local_env.LocalStructOrderParams)


            * [`LocalStructOrderParams.__supported_types`](pymatgen.analysis.md#pymatgen.analysis.local_env.LocalStructOrderParams.__supported_types)


            * [`LocalStructOrderParams.compute_trigonometric_terms()`](pymatgen.analysis.md#pymatgen.analysis.local_env.LocalStructOrderParams.compute_trigonometric_terms)


            * [`LocalStructOrderParams.get_order_parameters()`](pymatgen.analysis.md#pymatgen.analysis.local_env.LocalStructOrderParams.get_order_parameters)


            * [`LocalStructOrderParams.get_parameters()`](pymatgen.analysis.md#pymatgen.analysis.local_env.LocalStructOrderParams.get_parameters)


            * [`LocalStructOrderParams.get_q2()`](pymatgen.analysis.md#pymatgen.analysis.local_env.LocalStructOrderParams.get_q2)


            * [`LocalStructOrderParams.get_q4()`](pymatgen.analysis.md#pymatgen.analysis.local_env.LocalStructOrderParams.get_q4)


            * [`LocalStructOrderParams.get_q6()`](pymatgen.analysis.md#pymatgen.analysis.local_env.LocalStructOrderParams.get_q6)


            * [`LocalStructOrderParams.get_type()`](pymatgen.analysis.md#pymatgen.analysis.local_env.LocalStructOrderParams.get_type)


            * [`LocalStructOrderParams.last_nneigh`](pymatgen.analysis.md#pymatgen.analysis.local_env.LocalStructOrderParams.last_nneigh)


            * [`LocalStructOrderParams.num_ops`](pymatgen.analysis.md#pymatgen.analysis.local_env.LocalStructOrderParams.num_ops)


        * [`MinimumDistanceNN`](pymatgen.analysis.md#pymatgen.analysis.local_env.MinimumDistanceNN)


            * [`MinimumDistanceNN.extend_structure_molecules`](pymatgen.analysis.md#pymatgen.analysis.local_env.MinimumDistanceNN.extend_structure_molecules)


            * [`MinimumDistanceNN.get_nn_info()`](pymatgen.analysis.md#pymatgen.analysis.local_env.MinimumDistanceNN.get_nn_info)


            * [`MinimumDistanceNN.molecules_allowed`](pymatgen.analysis.md#pymatgen.analysis.local_env.MinimumDistanceNN.molecules_allowed)


            * [`MinimumDistanceNN.structures_allowed`](pymatgen.analysis.md#pymatgen.analysis.local_env.MinimumDistanceNN.structures_allowed)


        * [`MinimumOKeeffeNN`](pymatgen.analysis.md#pymatgen.analysis.local_env.MinimumOKeeffeNN)


            * [`MinimumOKeeffeNN.extend_structure_molecules`](pymatgen.analysis.md#pymatgen.analysis.local_env.MinimumOKeeffeNN.extend_structure_molecules)


            * [`MinimumOKeeffeNN.get_nn_info()`](pymatgen.analysis.md#pymatgen.analysis.local_env.MinimumOKeeffeNN.get_nn_info)


            * [`MinimumOKeeffeNN.molecules_allowed`](pymatgen.analysis.md#pymatgen.analysis.local_env.MinimumOKeeffeNN.molecules_allowed)


            * [`MinimumOKeeffeNN.structures_allowed`](pymatgen.analysis.md#pymatgen.analysis.local_env.MinimumOKeeffeNN.structures_allowed)


        * [`MinimumVIRENN`](pymatgen.analysis.md#pymatgen.analysis.local_env.MinimumVIRENN)


            * [`MinimumVIRENN.get_nn_info()`](pymatgen.analysis.md#pymatgen.analysis.local_env.MinimumVIRENN.get_nn_info)


            * [`MinimumVIRENN.molecules_allowed`](pymatgen.analysis.md#pymatgen.analysis.local_env.MinimumVIRENN.molecules_allowed)


            * [`MinimumVIRENN.structures_allowed`](pymatgen.analysis.md#pymatgen.analysis.local_env.MinimumVIRENN.structures_allowed)


        * [`NearNeighbors`](pymatgen.analysis.md#pymatgen.analysis.local_env.NearNeighbors)


            * [`NearNeighbors._get_image()`](pymatgen.analysis.md#pymatgen.analysis.local_env.NearNeighbors._get_image)


            * [`NearNeighbors._get_nn_shell_info()`](pymatgen.analysis.md#pymatgen.analysis.local_env.NearNeighbors._get_nn_shell_info)


            * [`NearNeighbors._get_original_site()`](pymatgen.analysis.md#pymatgen.analysis.local_env.NearNeighbors._get_original_site)


            * [`NearNeighbors.extend_structure_molecules`](pymatgen.analysis.md#pymatgen.analysis.local_env.NearNeighbors.extend_structure_molecules)


            * [`NearNeighbors.get_all_nn_info()`](pymatgen.analysis.md#pymatgen.analysis.local_env.NearNeighbors.get_all_nn_info)


            * [`NearNeighbors.get_bonded_structure()`](pymatgen.analysis.md#pymatgen.analysis.local_env.NearNeighbors.get_bonded_structure)


            * [`NearNeighbors.get_cn()`](pymatgen.analysis.md#pymatgen.analysis.local_env.NearNeighbors.get_cn)


            * [`NearNeighbors.get_cn_dict()`](pymatgen.analysis.md#pymatgen.analysis.local_env.NearNeighbors.get_cn_dict)


            * [`NearNeighbors.get_local_order_parameters()`](pymatgen.analysis.md#pymatgen.analysis.local_env.NearNeighbors.get_local_order_parameters)


            * [`NearNeighbors.get_nn()`](pymatgen.analysis.md#pymatgen.analysis.local_env.NearNeighbors.get_nn)


            * [`NearNeighbors.get_nn_images()`](pymatgen.analysis.md#pymatgen.analysis.local_env.NearNeighbors.get_nn_images)


            * [`NearNeighbors.get_nn_info()`](pymatgen.analysis.md#pymatgen.analysis.local_env.NearNeighbors.get_nn_info)


            * [`NearNeighbors.get_nn_shell_info()`](pymatgen.analysis.md#pymatgen.analysis.local_env.NearNeighbors.get_nn_shell_info)


            * [`NearNeighbors.get_weights_of_nn_sites()`](pymatgen.analysis.md#pymatgen.analysis.local_env.NearNeighbors.get_weights_of_nn_sites)


            * [`NearNeighbors.molecules_allowed`](pymatgen.analysis.md#pymatgen.analysis.local_env.NearNeighbors.molecules_allowed)


            * [`NearNeighbors.structures_allowed`](pymatgen.analysis.md#pymatgen.analysis.local_env.NearNeighbors.structures_allowed)


        * [`OpenBabelNN`](pymatgen.analysis.md#pymatgen.analysis.local_env.OpenBabelNN)


            * [`OpenBabelNN.extend_structure_molecules`](pymatgen.analysis.md#pymatgen.analysis.local_env.OpenBabelNN.extend_structure_molecules)


            * [`OpenBabelNN.get_bonded_structure()`](pymatgen.analysis.md#pymatgen.analysis.local_env.OpenBabelNN.get_bonded_structure)


            * [`OpenBabelNN.get_nn_info()`](pymatgen.analysis.md#pymatgen.analysis.local_env.OpenBabelNN.get_nn_info)


            * [`OpenBabelNN.get_nn_shell_info()`](pymatgen.analysis.md#pymatgen.analysis.local_env.OpenBabelNN.get_nn_shell_info)


            * [`OpenBabelNN.molecules_allowed`](pymatgen.analysis.md#pymatgen.analysis.local_env.OpenBabelNN.molecules_allowed)


            * [`OpenBabelNN.structures_allowed`](pymatgen.analysis.md#pymatgen.analysis.local_env.OpenBabelNN.structures_allowed)


        * [`ValenceIonicRadiusEvaluator`](pymatgen.analysis.md#pymatgen.analysis.local_env.ValenceIonicRadiusEvaluator)


            * [`ValenceIonicRadiusEvaluator._get_ionic_radii()`](pymatgen.analysis.md#pymatgen.analysis.local_env.ValenceIonicRadiusEvaluator._get_ionic_radii)


            * [`ValenceIonicRadiusEvaluator._get_valences()`](pymatgen.analysis.md#pymatgen.analysis.local_env.ValenceIonicRadiusEvaluator._get_valences)


            * [`ValenceIonicRadiusEvaluator.radii`](pymatgen.analysis.md#pymatgen.analysis.local_env.ValenceIonicRadiusEvaluator.radii)


            * [`ValenceIonicRadiusEvaluator.structure`](pymatgen.analysis.md#pymatgen.analysis.local_env.ValenceIonicRadiusEvaluator.structure)


            * [`ValenceIonicRadiusEvaluator.valences`](pymatgen.analysis.md#pymatgen.analysis.local_env.ValenceIonicRadiusEvaluator.valences)


        * [`VoronoiNN`](pymatgen.analysis.md#pymatgen.analysis.local_env.VoronoiNN)


            * [`VoronoiNN._extract_cell_info()`](pymatgen.analysis.md#pymatgen.analysis.local_env.VoronoiNN._extract_cell_info)


            * [`VoronoiNN._extract_nn_info()`](pymatgen.analysis.md#pymatgen.analysis.local_env.VoronoiNN._extract_nn_info)


            * [`VoronoiNN.get_all_nn_info()`](pymatgen.analysis.md#pymatgen.analysis.local_env.VoronoiNN.get_all_nn_info)


            * [`VoronoiNN.get_all_voronoi_polyhedra()`](pymatgen.analysis.md#pymatgen.analysis.local_env.VoronoiNN.get_all_voronoi_polyhedra)


            * [`VoronoiNN.get_nn_info()`](pymatgen.analysis.md#pymatgen.analysis.local_env.VoronoiNN.get_nn_info)


            * [`VoronoiNN.get_voronoi_polyhedra()`](pymatgen.analysis.md#pymatgen.analysis.local_env.VoronoiNN.get_voronoi_polyhedra)


            * [`VoronoiNN.molecules_allowed`](pymatgen.analysis.md#pymatgen.analysis.local_env.VoronoiNN.molecules_allowed)


            * [`VoronoiNN.structures_allowed`](pymatgen.analysis.md#pymatgen.analysis.local_env.VoronoiNN.structures_allowed)


        * [`_get_default_radius()`](pymatgen.analysis.md#pymatgen.analysis.local_env._get_default_radius)


        * [`_get_elements()`](pymatgen.analysis.md#pymatgen.analysis.local_env._get_elements)


        * [`_get_fictive_ionic_radius()`](pymatgen.analysis.md#pymatgen.analysis.local_env._get_fictive_ionic_radius)


        * [`_get_mean_fictive_ionic_radius()`](pymatgen.analysis.md#pymatgen.analysis.local_env._get_mean_fictive_ionic_radius)


        * [`_get_radius()`](pymatgen.analysis.md#pymatgen.analysis.local_env._get_radius)


        * [`_get_vire()`](pymatgen.analysis.md#pymatgen.analysis.local_env._get_vire)


        * [`_get_vire_istructure()`](pymatgen.analysis.md#pymatgen.analysis.local_env._get_vire_istructure)


        * [`_handle_disorder()`](pymatgen.analysis.md#pymatgen.analysis.local_env._handle_disorder)


        * [`_is_in_targets()`](pymatgen.analysis.md#pymatgen.analysis.local_env._is_in_targets)


        * [`get_neighbors_of_site_with_index()`](pymatgen.analysis.md#pymatgen.analysis.local_env.get_neighbors_of_site_with_index)


        * [`get_okeeffe_distance_prediction()`](pymatgen.analysis.md#pymatgen.analysis.local_env.get_okeeffe_distance_prediction)


        * [`get_okeeffe_params()`](pymatgen.analysis.md#pymatgen.analysis.local_env.get_okeeffe_params)


        * [`gramschmidt()`](pymatgen.analysis.md#pymatgen.analysis.local_env.gramschmidt)


        * [`metal_edge_extender()`](pymatgen.analysis.md#pymatgen.analysis.local_env.metal_edge_extender)


        * [`oxygen_edge_extender()`](pymatgen.analysis.md#pymatgen.analysis.local_env.oxygen_edge_extender)


        * [`site_is_of_motif_type()`](pymatgen.analysis.md#pymatgen.analysis.local_env.site_is_of_motif_type)


        * [`solid_angle()`](pymatgen.analysis.md#pymatgen.analysis.local_env.solid_angle)


        * [`vol_tetra()`](pymatgen.analysis.md#pymatgen.analysis.local_env.vol_tetra)


    * [pymatgen.analysis.molecule_matcher module](pymatgen.analysis.md#module-pymatgen.analysis.molecule_matcher)


        * [`AbstractMolAtomMapper`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.AbstractMolAtomMapper)


            * [`AbstractMolAtomMapper._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.AbstractMolAtomMapper._abc_impl)


            * [`AbstractMolAtomMapper.from_dict()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.AbstractMolAtomMapper.from_dict)


            * [`AbstractMolAtomMapper.get_molecule_hash()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.AbstractMolAtomMapper.get_molecule_hash)


            * [`AbstractMolAtomMapper.uniform_labels()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.AbstractMolAtomMapper.uniform_labels)


        * [`BruteForceOrderMatcher`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.BruteForceOrderMatcher)


            * [`BruteForceOrderMatcher.fit()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.BruteForceOrderMatcher.fit)


            * [`BruteForceOrderMatcher.match()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.BruteForceOrderMatcher.match)


            * [`BruteForceOrderMatcher.permutations()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.BruteForceOrderMatcher.permutations)


        * [`GeneticOrderMatcher`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.GeneticOrderMatcher)


            * [`GeneticOrderMatcher.fit()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.GeneticOrderMatcher.fit)


            * [`GeneticOrderMatcher.match()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.GeneticOrderMatcher.match)


            * [`GeneticOrderMatcher.permutations()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.GeneticOrderMatcher.permutations)


        * [`HungarianOrderMatcher`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.HungarianOrderMatcher)


            * [`HungarianOrderMatcher.fit()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.HungarianOrderMatcher.fit)


            * [`HungarianOrderMatcher.get_principal_axis()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.HungarianOrderMatcher.get_principal_axis)


            * [`HungarianOrderMatcher.match()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.HungarianOrderMatcher.match)


            * [`HungarianOrderMatcher.permutations()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.HungarianOrderMatcher.permutations)


            * [`HungarianOrderMatcher.rotation_matrix_vectors()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.HungarianOrderMatcher.rotation_matrix_vectors)


        * [`InchiMolAtomMapper`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.InchiMolAtomMapper)


            * [`InchiMolAtomMapper._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.InchiMolAtomMapper._abc_impl)


            * [`InchiMolAtomMapper._align_heavy_atoms()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.InchiMolAtomMapper._align_heavy_atoms)


            * [`InchiMolAtomMapper._align_hydrogen_atoms()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.InchiMolAtomMapper._align_hydrogen_atoms)


            * [`InchiMolAtomMapper._get_elements()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.InchiMolAtomMapper._get_elements)


            * [`InchiMolAtomMapper._group_centroid()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.InchiMolAtomMapper._group_centroid)


            * [`InchiMolAtomMapper._inchi_labels()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.InchiMolAtomMapper._inchi_labels)


            * [`InchiMolAtomMapper._is_molecule_linear()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.InchiMolAtomMapper._is_molecule_linear)


            * [`InchiMolAtomMapper._virtual_molecule()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.InchiMolAtomMapper._virtual_molecule)


            * [`InchiMolAtomMapper.as_dict()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.InchiMolAtomMapper.as_dict)


            * [`InchiMolAtomMapper.from_dict()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.InchiMolAtomMapper.from_dict)


            * [`InchiMolAtomMapper.get_molecule_hash()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.InchiMolAtomMapper.get_molecule_hash)


            * [`InchiMolAtomMapper.uniform_labels()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.InchiMolAtomMapper.uniform_labels)


        * [`IsomorphismMolAtomMapper`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.IsomorphismMolAtomMapper)


            * [`IsomorphismMolAtomMapper._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.IsomorphismMolAtomMapper._abc_impl)


            * [`IsomorphismMolAtomMapper.as_dict()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.IsomorphismMolAtomMapper.as_dict)


            * [`IsomorphismMolAtomMapper.from_dict()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.IsomorphismMolAtomMapper.from_dict)


            * [`IsomorphismMolAtomMapper.get_molecule_hash()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.IsomorphismMolAtomMapper.get_molecule_hash)


            * [`IsomorphismMolAtomMapper.uniform_labels()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.IsomorphismMolAtomMapper.uniform_labels)


        * [`KabschMatcher`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.KabschMatcher)


            * [`KabschMatcher.fit()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.KabschMatcher.fit)


            * [`KabschMatcher.kabsch()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.KabschMatcher.kabsch)


            * [`KabschMatcher.match()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.KabschMatcher.match)


        * [`MoleculeMatcher`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.MoleculeMatcher)


            * [`MoleculeMatcher._calc_rms()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.MoleculeMatcher._calc_rms)


            * [`MoleculeMatcher.as_dict()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.MoleculeMatcher.as_dict)


            * [`MoleculeMatcher.fit()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.MoleculeMatcher.fit)


            * [`MoleculeMatcher.from_dict()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.MoleculeMatcher.from_dict)


            * [`MoleculeMatcher.get_rmsd()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.MoleculeMatcher.get_rmsd)


            * [`MoleculeMatcher.group_molecules()`](pymatgen.analysis.md#pymatgen.analysis.molecule_matcher.MoleculeMatcher.group_molecules)


    * [pymatgen.analysis.molecule_structure_comparator module](pymatgen.analysis.md#module-pymatgen.analysis.molecule_structure_comparator)


        * [`CovalentRadius`](pymatgen.analysis.md#pymatgen.analysis.molecule_structure_comparator.CovalentRadius)


            * [`CovalentRadius.radius`](pymatgen.analysis.md#pymatgen.analysis.molecule_structure_comparator.CovalentRadius.radius)


        * [`MoleculeStructureComparator`](pymatgen.analysis.md#pymatgen.analysis.molecule_structure_comparator.MoleculeStructureComparator)


            * [`MoleculeStructureComparator._get_bonds()`](pymatgen.analysis.md#pymatgen.analysis.molecule_structure_comparator.MoleculeStructureComparator._get_bonds)


            * [`MoleculeStructureComparator.are_equal()`](pymatgen.analysis.md#pymatgen.analysis.molecule_structure_comparator.MoleculeStructureComparator.are_equal)


            * [`MoleculeStructureComparator.as_dict()`](pymatgen.analysis.md#pymatgen.analysis.molecule_structure_comparator.MoleculeStructureComparator.as_dict)


            * [`MoleculeStructureComparator.from_dict()`](pymatgen.analysis.md#pymatgen.analysis.molecule_structure_comparator.MoleculeStructureComparator.from_dict)


            * [`MoleculeStructureComparator.get_13_bonds()`](pymatgen.analysis.md#pymatgen.analysis.molecule_structure_comparator.MoleculeStructureComparator.get_13_bonds)


            * [`MoleculeStructureComparator.halogen_list`](pymatgen.analysis.md#pymatgen.analysis.molecule_structure_comparator.MoleculeStructureComparator.halogen_list)


            * [`MoleculeStructureComparator.ionic_element_list`](pymatgen.analysis.md#pymatgen.analysis.molecule_structure_comparator.MoleculeStructureComparator.ionic_element_list)


    * [pymatgen.analysis.nmr module](pymatgen.analysis.md#module-pymatgen.analysis.nmr)


        * [`ChemicalShielding`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding)


            * [`ChemicalShielding.HaeberlenNotation`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.HaeberlenNotation)


                * [`ChemicalShielding.HaeberlenNotation._asdict()`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.HaeberlenNotation._asdict)


                * [`ChemicalShielding.HaeberlenNotation._field_defaults`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.HaeberlenNotation._field_defaults)


                * [`ChemicalShielding.HaeberlenNotation._fields`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.HaeberlenNotation._fields)


                * [`ChemicalShielding.HaeberlenNotation._make()`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.HaeberlenNotation._make)


                * [`ChemicalShielding.HaeberlenNotation._replace()`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.HaeberlenNotation._replace)


                * [`ChemicalShielding.HaeberlenNotation.delta_sigma_iso`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.HaeberlenNotation.delta_sigma_iso)


                * [`ChemicalShielding.HaeberlenNotation.eta`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.HaeberlenNotation.eta)


                * [`ChemicalShielding.HaeberlenNotation.sigma_iso`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.HaeberlenNotation.sigma_iso)


                * [`ChemicalShielding.HaeberlenNotation.zeta`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.HaeberlenNotation.zeta)


            * [`ChemicalShielding.MarylandNotation`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.MarylandNotation)


                * [`ChemicalShielding.MarylandNotation._asdict()`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.MarylandNotation._asdict)


                * [`ChemicalShielding.MarylandNotation._field_defaults`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.MarylandNotation._field_defaults)


                * [`ChemicalShielding.MarylandNotation._fields`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.MarylandNotation._fields)


                * [`ChemicalShielding.MarylandNotation._make()`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.MarylandNotation._make)


                * [`ChemicalShielding.MarylandNotation._replace()`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.MarylandNotation._replace)


                * [`ChemicalShielding.MarylandNotation.kappa`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.MarylandNotation.kappa)


                * [`ChemicalShielding.MarylandNotation.omega`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.MarylandNotation.omega)


                * [`ChemicalShielding.MarylandNotation.sigma_iso`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.MarylandNotation.sigma_iso)


            * [`ChemicalShielding.MehringNotation`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.MehringNotation)


                * [`ChemicalShielding.MehringNotation._asdict()`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.MehringNotation._asdict)


                * [`ChemicalShielding.MehringNotation._field_defaults`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.MehringNotation._field_defaults)


                * [`ChemicalShielding.MehringNotation._fields`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.MehringNotation._fields)


                * [`ChemicalShielding.MehringNotation._make()`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.MehringNotation._make)


                * [`ChemicalShielding.MehringNotation._replace()`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.MehringNotation._replace)


                * [`ChemicalShielding.MehringNotation.sigma_11`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.MehringNotation.sigma_11)


                * [`ChemicalShielding.MehringNotation.sigma_22`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.MehringNotation.sigma_22)


                * [`ChemicalShielding.MehringNotation.sigma_33`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.MehringNotation.sigma_33)


                * [`ChemicalShielding.MehringNotation.sigma_iso`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.MehringNotation.sigma_iso)


            * [`ChemicalShielding.from_maryland_notation()`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.from_maryland_notation)


            * [`ChemicalShielding.haeberlen_values`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.haeberlen_values)


            * [`ChemicalShielding.maryland_values`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.maryland_values)


            * [`ChemicalShielding.mehring_values`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.mehring_values)


            * [`ChemicalShielding.principal_axis_system`](pymatgen.analysis.md#pymatgen.analysis.nmr.ChemicalShielding.principal_axis_system)


        * [`ElectricFieldGradient`](pymatgen.analysis.md#pymatgen.analysis.nmr.ElectricFieldGradient)


            * [`ElectricFieldGradient.V_xx`](pymatgen.analysis.md#pymatgen.analysis.nmr.ElectricFieldGradient.V_xx)


            * [`ElectricFieldGradient.V_yy`](pymatgen.analysis.md#pymatgen.analysis.nmr.ElectricFieldGradient.V_yy)


            * [`ElectricFieldGradient.V_zz`](pymatgen.analysis.md#pymatgen.analysis.nmr.ElectricFieldGradient.V_zz)


            * [`ElectricFieldGradient.asymmetry`](pymatgen.analysis.md#pymatgen.analysis.nmr.ElectricFieldGradient.asymmetry)


            * [`ElectricFieldGradient.coupling_constant()`](pymatgen.analysis.md#pymatgen.analysis.nmr.ElectricFieldGradient.coupling_constant)


            * [`ElectricFieldGradient.principal_axis_system`](pymatgen.analysis.md#pymatgen.analysis.nmr.ElectricFieldGradient.principal_axis_system)


    * [pymatgen.analysis.phase_diagram module](pymatgen.analysis.md#module-pymatgen.analysis.phase_diagram)


        * [`CompoundPhaseDiagram`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.CompoundPhaseDiagram)


            * [`CompoundPhaseDiagram.amount_tol`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.CompoundPhaseDiagram.amount_tol)


            * [`CompoundPhaseDiagram.as_dict()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.CompoundPhaseDiagram.as_dict)


            * [`CompoundPhaseDiagram.from_dict()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.CompoundPhaseDiagram.from_dict)


            * [`CompoundPhaseDiagram.transform_entries()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.CompoundPhaseDiagram.transform_entries)


        * [`GrandPotPDEntry`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.GrandPotPDEntry)


            * [`GrandPotPDEntry._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.GrandPotPDEntry._abc_impl)


            * [`GrandPotPDEntry.as_dict()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.GrandPotPDEntry.as_dict)


            * [`GrandPotPDEntry.chemical_energy`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.GrandPotPDEntry.chemical_energy)


            * [`GrandPotPDEntry.composition`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.GrandPotPDEntry.composition)


            * [`GrandPotPDEntry.energy`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.GrandPotPDEntry.energy)


            * [`GrandPotPDEntry.from_dict()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.GrandPotPDEntry.from_dict)


        * [`GrandPotentialPhaseDiagram`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.GrandPotentialPhaseDiagram)


            * [`GrandPotentialPhaseDiagram.as_dict()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.GrandPotentialPhaseDiagram.as_dict)


            * [`GrandPotentialPhaseDiagram.from_dict()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.GrandPotentialPhaseDiagram.from_dict)


        * [`PDEntry`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PDEntry)


            * [`PDEntry.composition`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PDEntry.composition)


            * [`PDEntry.energy`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PDEntry.energy)


            * [`PDEntry.name`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PDEntry.name)


            * [`PDEntry.attribute`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PDEntry.attribute)


            * [`PDEntry._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PDEntry._abc_impl)


            * [`PDEntry.as_dict()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PDEntry.as_dict)


            * [`PDEntry.energy`](pymatgen.analysis.md#id0)


            * [`PDEntry.from_dict()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PDEntry.from_dict)


        * [`PDPlotter`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PDPlotter)


            * [`PDPlotter._create_plotly_element_annotations()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PDPlotter._create_plotly_element_annotations)


            * [`PDPlotter._create_plotly_figure_layout()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PDPlotter._create_plotly_figure_layout)


            * [`PDPlotter._create_plotly_fill()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PDPlotter._create_plotly_fill)


            * [`PDPlotter._create_plotly_lines()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PDPlotter._create_plotly_lines)


            * [`PDPlotter._create_plotly_markers()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PDPlotter._create_plotly_markers)


            * [`PDPlotter._create_plotly_stable_labels()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PDPlotter._create_plotly_stable_labels)


            * [`PDPlotter._create_plotly_ternary_support_lines()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PDPlotter._create_plotly_ternary_support_lines)


            * [`PDPlotter._create_plotly_uncertainty_shading()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PDPlotter._create_plotly_uncertainty_shading)


            * [`PDPlotter._get_matplotlib_2d_plot()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PDPlotter._get_matplotlib_2d_plot)


            * [`PDPlotter._get_matplotlib_3d_plot()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PDPlotter._get_matplotlib_3d_plot)


            * [`PDPlotter.get_chempot_range_map_plot()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PDPlotter.get_chempot_range_map_plot)


            * [`PDPlotter.get_contour_pd_plot()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PDPlotter.get_contour_pd_plot)


            * [`PDPlotter.get_plot()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PDPlotter.get_plot)


            * [`PDPlotter.pd_plot_data`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PDPlotter.pd_plot_data)


            * [`PDPlotter.plot_chempot_range_map()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PDPlotter.plot_chempot_range_map)


            * [`PDPlotter.plot_element_profile()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PDPlotter.plot_element_profile)


            * [`PDPlotter.show()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PDPlotter.show)


            * [`PDPlotter.write_image()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PDPlotter.write_image)


        * [`PatchedPhaseDiagram`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PatchedPhaseDiagram)


            * [`PatchedPhaseDiagram.all_entries`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PatchedPhaseDiagram.all_entries)


            * [`PatchedPhaseDiagram.min_entries`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PatchedPhaseDiagram.min_entries)


            * [`PatchedPhaseDiagram.el_refs`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PatchedPhaseDiagram.el_refs)


            * [`PatchedPhaseDiagram.elements`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PatchedPhaseDiagram.elements)


            * [`PatchedPhaseDiagram._get_all_facets_and_simplexes()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PatchedPhaseDiagram._get_all_facets_and_simplexes)


            * [`PatchedPhaseDiagram._get_facet_and_simplex()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PatchedPhaseDiagram._get_facet_and_simplex)


            * [`PatchedPhaseDiagram._get_facet_chempots()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PatchedPhaseDiagram._get_facet_chempots)


            * [`PatchedPhaseDiagram._get_pd_patch_for_space()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PatchedPhaseDiagram._get_pd_patch_for_space)


            * [`PatchedPhaseDiagram._get_simplex_intersections()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PatchedPhaseDiagram._get_simplex_intersections)


            * [`PatchedPhaseDiagram.as_dict()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PatchedPhaseDiagram.as_dict)


            * [`PatchedPhaseDiagram.from_dict()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PatchedPhaseDiagram.from_dict)


            * [`PatchedPhaseDiagram.get_all_chempots()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PatchedPhaseDiagram.get_all_chempots)


            * [`PatchedPhaseDiagram.get_chempot_range_map()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PatchedPhaseDiagram.get_chempot_range_map)


            * [`PatchedPhaseDiagram.get_chempot_range_stability_phase()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PatchedPhaseDiagram.get_chempot_range_stability_phase)


            * [`PatchedPhaseDiagram.get_composition_chempots()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PatchedPhaseDiagram.get_composition_chempots)


            * [`PatchedPhaseDiagram.get_critical_compositions()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PatchedPhaseDiagram.get_critical_compositions)


            * [`PatchedPhaseDiagram.get_decomp_and_e_above_hull()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PatchedPhaseDiagram.get_decomp_and_e_above_hull)


            * [`PatchedPhaseDiagram.get_decomposition()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PatchedPhaseDiagram.get_decomposition)


            * [`PatchedPhaseDiagram.get_element_profile()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PatchedPhaseDiagram.get_element_profile)


            * [`PatchedPhaseDiagram.get_equilibrium_reaction_energy()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PatchedPhaseDiagram.get_equilibrium_reaction_energy)


            * [`PatchedPhaseDiagram.get_pd_for_entry()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PatchedPhaseDiagram.get_pd_for_entry)


            * [`PatchedPhaseDiagram.get_transition_chempots()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PatchedPhaseDiagram.get_transition_chempots)


            * [`PatchedPhaseDiagram.getmu_vertices_stability_phase()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PatchedPhaseDiagram.getmu_vertices_stability_phase)


        * [`PhaseDiagram`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram)


            * [`PhaseDiagram.dim`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.dim)


            * [`PhaseDiagram.elements`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.elements)


            * [`PhaseDiagram.el_refs`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.el_refs)


            * [`PhaseDiagram.all_entries`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.all_entries)


            * [`PhaseDiagram.qhull_entries`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.qhull_entries)


            * [`PhaseDiagram.qhull_data`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.qhull_data)


            * [`PhaseDiagram.facets`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.facets)


            * [`PhaseDiagram.simplices`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.simplices)


            * [`PhaseDiagram._compute()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram._compute)


            * [`PhaseDiagram._get_all_facets_and_simplexes()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram._get_all_facets_and_simplexes)


            * [`PhaseDiagram._get_facet_and_simplex()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram._get_facet_and_simplex)


            * [`PhaseDiagram._get_facet_chempots()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram._get_facet_chempots)


            * [`PhaseDiagram._get_simplex_intersections()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram._get_simplex_intersections)


            * [`PhaseDiagram._get_stable_entries_in_space()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram._get_stable_entries_in_space)


            * [`PhaseDiagram.all_entries_hulldata`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.all_entries_hulldata)


            * [`PhaseDiagram.as_dict()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.as_dict)


            * [`PhaseDiagram.formation_energy_tol`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.formation_energy_tol)


            * [`PhaseDiagram.from_dict()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.from_dict)


            * [`PhaseDiagram.get_all_chempots()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.get_all_chempots)


            * [`PhaseDiagram.get_chempot_range_map()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.get_chempot_range_map)


            * [`PhaseDiagram.get_chempot_range_stability_phase()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.get_chempot_range_stability_phase)


            * [`PhaseDiagram.get_composition_chempots()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.get_composition_chempots)


            * [`PhaseDiagram.get_critical_compositions()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.get_critical_compositions)


            * [`PhaseDiagram.get_decomp_and_e_above_hull()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.get_decomp_and_e_above_hull)


            * [`PhaseDiagram.get_decomp_and_hull_energy_per_atom()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.get_decomp_and_hull_energy_per_atom)


            * [`PhaseDiagram.get_decomp_and_phase_separation_energy()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.get_decomp_and_phase_separation_energy)


            * [`PhaseDiagram.get_decomposition()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.get_decomposition)


            * [`PhaseDiagram.get_e_above_hull()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.get_e_above_hull)


            * [`PhaseDiagram.get_element_profile()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.get_element_profile)


            * [`PhaseDiagram.get_equilibrium_reaction_energy()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.get_equilibrium_reaction_energy)


            * [`PhaseDiagram.get_form_energy()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.get_form_energy)


            * [`PhaseDiagram.get_form_energy_per_atom()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.get_form_energy_per_atom)


            * [`PhaseDiagram.get_hull_energy()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.get_hull_energy)


            * [`PhaseDiagram.get_hull_energy_per_atom()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.get_hull_energy_per_atom)


            * [`PhaseDiagram.get_phase_separation_energy()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.get_phase_separation_energy)


            * [`PhaseDiagram.get_plot()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.get_plot)


            * [`PhaseDiagram.get_reference_energy()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.get_reference_energy)


            * [`PhaseDiagram.get_reference_energy_per_atom()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.get_reference_energy_per_atom)


            * [`PhaseDiagram.get_transition_chempots()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.get_transition_chempots)


            * [`PhaseDiagram.getmu_vertices_stability_phase()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.getmu_vertices_stability_phase)


            * [`PhaseDiagram.numerical_tol`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.numerical_tol)


            * [`PhaseDiagram.pd_coords()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.pd_coords)


            * [`PhaseDiagram.stable_entries`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.stable_entries)


            * [`PhaseDiagram.unstable_entries`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagram.unstable_entries)


        * [`PhaseDiagramError`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.PhaseDiagramError)


        * [`ReactionDiagram`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.ReactionDiagram)


            * [`ReactionDiagram.get_compound_pd()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.ReactionDiagram.get_compound_pd)


        * [`TransformedPDEntry`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.TransformedPDEntry)


            * [`TransformedPDEntry._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.TransformedPDEntry._abc_impl)


            * [`TransformedPDEntry.amount_tol`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.TransformedPDEntry.amount_tol)


            * [`TransformedPDEntry.as_dict()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.TransformedPDEntry.as_dict)


            * [`TransformedPDEntry.composition`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.TransformedPDEntry.composition)


            * [`TransformedPDEntry.from_dict()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.TransformedPDEntry.from_dict)


        * [`TransformedPDEntryError`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.TransformedPDEntryError)


        * [`_get_slsqp_decomp()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram._get_slsqp_decomp)


        * [`get_facets()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.get_facets)


        * [`order_phase_diagram()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.order_phase_diagram)


        * [`tet_coord()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.tet_coord)


        * [`triangular_coord()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.triangular_coord)


        * [`uniquelines()`](pymatgen.analysis.md#pymatgen.analysis.phase_diagram.uniquelines)


    * [pymatgen.analysis.piezo module](pymatgen.analysis.md#module-pymatgen.analysis.piezo)


        * [`PiezoTensor`](pymatgen.analysis.md#pymatgen.analysis.piezo.PiezoTensor)


            * [`PiezoTensor.from_vasp_voigt()`](pymatgen.analysis.md#pymatgen.analysis.piezo.PiezoTensor.from_vasp_voigt)


    * [pymatgen.analysis.piezo_sensitivity module](pymatgen.analysis.md#module-pymatgen.analysis.piezo_sensitivity)


        * [`BornEffectiveCharge`](pymatgen.analysis.md#pymatgen.analysis.piezo_sensitivity.BornEffectiveCharge)


            * [`BornEffectiveCharge.get_BEC_operations()`](pymatgen.analysis.md#pymatgen.analysis.piezo_sensitivity.BornEffectiveCharge.get_BEC_operations)


            * [`BornEffectiveCharge.get_rand_BEC()`](pymatgen.analysis.md#pymatgen.analysis.piezo_sensitivity.BornEffectiveCharge.get_rand_BEC)


        * [`ForceConstantMatrix`](pymatgen.analysis.md#pymatgen.analysis.piezo_sensitivity.ForceConstantMatrix)


            * [`ForceConstantMatrix.get_FCM_operations()`](pymatgen.analysis.md#pymatgen.analysis.piezo_sensitivity.ForceConstantMatrix.get_FCM_operations)


            * [`ForceConstantMatrix.get_asum_FCM()`](pymatgen.analysis.md#pymatgen.analysis.piezo_sensitivity.ForceConstantMatrix.get_asum_FCM)


            * [`ForceConstantMatrix.get_rand_FCM()`](pymatgen.analysis.md#pymatgen.analysis.piezo_sensitivity.ForceConstantMatrix.get_rand_FCM)


            * [`ForceConstantMatrix.get_stable_FCM()`](pymatgen.analysis.md#pymatgen.analysis.piezo_sensitivity.ForceConstantMatrix.get_stable_FCM)


            * [`ForceConstantMatrix.get_symmetrized_FCM()`](pymatgen.analysis.md#pymatgen.analysis.piezo_sensitivity.ForceConstantMatrix.get_symmetrized_FCM)


            * [`ForceConstantMatrix.get_unstable_FCM()`](pymatgen.analysis.md#pymatgen.analysis.piezo_sensitivity.ForceConstantMatrix.get_unstable_FCM)


        * [`InternalStrainTensor`](pymatgen.analysis.md#pymatgen.analysis.piezo_sensitivity.InternalStrainTensor)


            * [`InternalStrainTensor.get_IST_operations()`](pymatgen.analysis.md#pymatgen.analysis.piezo_sensitivity.InternalStrainTensor.get_IST_operations)


            * [`InternalStrainTensor.get_rand_IST()`](pymatgen.analysis.md#pymatgen.analysis.piezo_sensitivity.InternalStrainTensor.get_rand_IST)


        * [`get_piezo()`](pymatgen.analysis.md#pymatgen.analysis.piezo_sensitivity.get_piezo)


        * [`rand_piezo()`](pymatgen.analysis.md#pymatgen.analysis.piezo_sensitivity.rand_piezo)


    * [pymatgen.analysis.pourbaix_diagram module](pymatgen.analysis.md#module-pymatgen.analysis.pourbaix_diagram)


        * [`IonEntry`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.IonEntry)


            * [`IonEntry.name`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.IonEntry.name)


            * [`IonEntry._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.IonEntry._abc_impl)


            * [`IonEntry.as_dict()`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.IonEntry.as_dict)


            * [`IonEntry.from_dict()`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.IonEntry.from_dict)


        * [`MultiEntry`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.MultiEntry)


            * [`MultiEntry.as_dict()`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.MultiEntry.as_dict)


            * [`MultiEntry.from_dict()`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.MultiEntry.from_dict)


            * [`MultiEntry.name`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.MultiEntry.name)


        * [`PourbaixDiagram`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixDiagram)


            * [`PourbaixDiagram._convert_entries_to_points()`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixDiagram._convert_entries_to_points)


            * [`PourbaixDiagram._generate_multielement_entries()`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixDiagram._generate_multielement_entries)


            * [`PourbaixDiagram._get_hull_in_nph_nphi_space()`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixDiagram._get_hull_in_nph_nphi_space)


            * [`PourbaixDiagram._preprocess_pourbaix_entries()`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixDiagram._preprocess_pourbaix_entries)


            * [`PourbaixDiagram.all_entries`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixDiagram.all_entries)


            * [`PourbaixDiagram.as_dict()`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixDiagram.as_dict)


            * [`PourbaixDiagram.find_stable_entry()`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixDiagram.find_stable_entry)


            * [`PourbaixDiagram.from_dict()`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixDiagram.from_dict)


            * [`PourbaixDiagram.get_decomposition_energy()`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixDiagram.get_decomposition_energy)


            * [`PourbaixDiagram.get_hull_energy()`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixDiagram.get_hull_energy)


            * [`PourbaixDiagram.get_pourbaix_domains()`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixDiagram.get_pourbaix_domains)


            * [`PourbaixDiagram.get_stable_entry()`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixDiagram.get_stable_entry)


            * [`PourbaixDiagram.process_multientry()`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixDiagram.process_multientry)


            * [`PourbaixDiagram.stable_entries`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixDiagram.stable_entries)


            * [`PourbaixDiagram.unprocessed_entries`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixDiagram.unprocessed_entries)


            * [`PourbaixDiagram.unstable_entries`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixDiagram.unstable_entries)


        * [`PourbaixEntry`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixEntry)


            * [`PourbaixEntry.as_dict()`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixEntry.as_dict)


            * [`PourbaixEntry.composition`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixEntry.composition)


            * [`PourbaixEntry.conc_term`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixEntry.conc_term)


            * [`PourbaixEntry.elements`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixEntry.elements)


            * [`PourbaixEntry.energy`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixEntry.energy)


            * [`PourbaixEntry.energy_at_conditions()`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixEntry.energy_at_conditions)


            * [`PourbaixEntry.energy_per_atom`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixEntry.energy_per_atom)


            * [`PourbaixEntry.from_dict()`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixEntry.from_dict)


            * [`PourbaixEntry.get_element_fraction()`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixEntry.get_element_fraction)


            * [`PourbaixEntry.nH2O`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixEntry.nH2O)


            * [`PourbaixEntry.nPhi`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixEntry.nPhi)


            * [`PourbaixEntry.name`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixEntry.name)


            * [`PourbaixEntry.normalization_factor`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixEntry.normalization_factor)


            * [`PourbaixEntry.normalized_energy`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixEntry.normalized_energy)


            * [`PourbaixEntry.normalized_energy_at_conditions()`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixEntry.normalized_energy_at_conditions)


            * [`PourbaixEntry.npH`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixEntry.npH)


            * [`PourbaixEntry.num_atoms`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixEntry.num_atoms)


            * [`PourbaixEntry.to_pretty_string()`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixEntry.to_pretty_string)


        * [`PourbaixPlotter`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixPlotter)


            * [`PourbaixPlotter.domain_vertices()`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixPlotter.domain_vertices)


            * [`PourbaixPlotter.get_pourbaix_plot()`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixPlotter.get_pourbaix_plot)


            * [`PourbaixPlotter.plot_entry_stability()`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixPlotter.plot_entry_stability)


            * [`PourbaixPlotter.show()`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.PourbaixPlotter.show)


        * [`generate_entry_label()`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.generate_entry_label)


        * [`ion_or_solid_comp_object()`](pymatgen.analysis.md#pymatgen.analysis.pourbaix_diagram.ion_or_solid_comp_object)


    * [pymatgen.analysis.prototypes module](pymatgen.analysis.md#module-pymatgen.analysis.prototypes)


        * [`AflowPrototypeMatcher`](pymatgen.analysis.md#pymatgen.analysis.prototypes.AflowPrototypeMatcher)


            * [`AflowPrototypeMatcher._match_prototype()`](pymatgen.analysis.md#pymatgen.analysis.prototypes.AflowPrototypeMatcher._match_prototype)


            * [`AflowPrototypeMatcher._match_single_prototype()`](pymatgen.analysis.md#pymatgen.analysis.prototypes.AflowPrototypeMatcher._match_single_prototype)


            * [`AflowPrototypeMatcher.get_prototypes()`](pymatgen.analysis.md#pymatgen.analysis.prototypes.AflowPrototypeMatcher.get_prototypes)


    * [pymatgen.analysis.quasiharmonic module](pymatgen.analysis.md#module-pymatgen.analysis.quasiharmonic)


        * [`QuasiharmonicDebyeApprox`](pymatgen.analysis.md#pymatgen.analysis.quasiharmonic.QuasiharmonicDebyeApprox)


            * [`QuasiharmonicDebyeApprox.debye_integral()`](pymatgen.analysis.md#pymatgen.analysis.quasiharmonic.QuasiharmonicDebyeApprox.debye_integral)


            * [`QuasiharmonicDebyeApprox.debye_temperature()`](pymatgen.analysis.md#pymatgen.analysis.quasiharmonic.QuasiharmonicDebyeApprox.debye_temperature)


            * [`QuasiharmonicDebyeApprox.get_summary_dict()`](pymatgen.analysis.md#pymatgen.analysis.quasiharmonic.QuasiharmonicDebyeApprox.get_summary_dict)


            * [`QuasiharmonicDebyeApprox.gruneisen_parameter()`](pymatgen.analysis.md#pymatgen.analysis.quasiharmonic.QuasiharmonicDebyeApprox.gruneisen_parameter)


            * [`QuasiharmonicDebyeApprox.optimize_gibbs_free_energy()`](pymatgen.analysis.md#pymatgen.analysis.quasiharmonic.QuasiharmonicDebyeApprox.optimize_gibbs_free_energy)


            * [`QuasiharmonicDebyeApprox.optimizer()`](pymatgen.analysis.md#pymatgen.analysis.quasiharmonic.QuasiharmonicDebyeApprox.optimizer)


            * [`QuasiharmonicDebyeApprox.thermal_conductivity()`](pymatgen.analysis.md#pymatgen.analysis.quasiharmonic.QuasiharmonicDebyeApprox.thermal_conductivity)


            * [`QuasiharmonicDebyeApprox.vibrational_free_energy()`](pymatgen.analysis.md#pymatgen.analysis.quasiharmonic.QuasiharmonicDebyeApprox.vibrational_free_energy)


            * [`QuasiharmonicDebyeApprox.vibrational_internal_energy()`](pymatgen.analysis.md#pymatgen.analysis.quasiharmonic.QuasiharmonicDebyeApprox.vibrational_internal_energy)


    * [pymatgen.analysis.quasirrho module](pymatgen.analysis.md#module-pymatgen.analysis.quasirrho)


        * [`QuasiRRHO`](pymatgen.analysis.md#pymatgen.analysis.quasirrho.QuasiRRHO)


            * [`QuasiRRHO.temp`](pymatgen.analysis.md#pymatgen.analysis.quasirrho.QuasiRRHO.temp)


            * [`QuasiRRHO.press`](pymatgen.analysis.md#pymatgen.analysis.quasirrho.QuasiRRHO.press)


            * [`QuasiRRHO.v0`](pymatgen.analysis.md#pymatgen.analysis.quasirrho.QuasiRRHO.v0)


            * [`QuasiRRHO.entropy_quasiRRHO`](pymatgen.analysis.md#pymatgen.analysis.quasirrho.QuasiRRHO.entropy_quasiRRHO)


            * [`QuasiRRHO.entropy_ho`](pymatgen.analysis.md#pymatgen.analysis.quasirrho.QuasiRRHO.entropy_ho)


            * [`QuasiRRHO.h_corrected`](pymatgen.analysis.md#pymatgen.analysis.quasirrho.QuasiRRHO.h_corrected)


            * [`QuasiRRHO.free_energy_quasiRRHO`](pymatgen.analysis.md#pymatgen.analysis.quasirrho.QuasiRRHO.free_energy_quasiRRHO)


            * [`QuasiRRHO.free_energy_ho`](pymatgen.analysis.md#pymatgen.analysis.quasirrho.QuasiRRHO.free_energy_ho)


            * [`QuasiRRHO._get_quasirrho_thermo()`](pymatgen.analysis.md#pymatgen.analysis.quasirrho.QuasiRRHO._get_quasirrho_thermo)


            * [`QuasiRRHO.from_gaussian_output()`](pymatgen.analysis.md#pymatgen.analysis.quasirrho.QuasiRRHO.from_gaussian_output)


            * [`QuasiRRHO.from_qc_output()`](pymatgen.analysis.md#pymatgen.analysis.quasirrho.QuasiRRHO.from_qc_output)


        * [`get_avg_mom_inertia()`](pymatgen.analysis.md#pymatgen.analysis.quasirrho.get_avg_mom_inertia)


    * [pymatgen.analysis.reaction_calculator module](pymatgen.analysis.md#module-pymatgen.analysis.reaction_calculator)


        * [`BalancedReaction`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.BalancedReaction)


            * [`BalancedReaction.TOLERANCE`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.BalancedReaction.TOLERANCE)


            * [`BalancedReaction._str_from_comp()`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.BalancedReaction._str_from_comp)


            * [`BalancedReaction._str_from_formulas()`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.BalancedReaction._str_from_formulas)


            * [`BalancedReaction.all_comp`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.BalancedReaction.all_comp)


            * [`BalancedReaction.as_dict()`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.BalancedReaction.as_dict)


            * [`BalancedReaction.as_entry()`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.BalancedReaction.as_entry)


            * [`BalancedReaction.calculate_energy()`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.BalancedReaction.calculate_energy)


            * [`BalancedReaction.coeffs`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.BalancedReaction.coeffs)


            * [`BalancedReaction.elements`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.BalancedReaction.elements)


            * [`BalancedReaction.from_dict()`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.BalancedReaction.from_dict)


            * [`BalancedReaction.from_str()`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.BalancedReaction.from_str)


            * [`BalancedReaction.from_string()`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.BalancedReaction.from_string)


            * [`BalancedReaction.get_coeff()`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.BalancedReaction.get_coeff)


            * [`BalancedReaction.get_el_amount()`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.BalancedReaction.get_el_amount)


            * [`BalancedReaction.normalize_to()`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.BalancedReaction.normalize_to)


            * [`BalancedReaction.normalize_to_element()`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.BalancedReaction.normalize_to_element)


            * [`BalancedReaction.normalized_repr`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.BalancedReaction.normalized_repr)


            * [`BalancedReaction.normalized_repr_and_factor()`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.BalancedReaction.normalized_repr_and_factor)


            * [`BalancedReaction.products`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.BalancedReaction.products)


            * [`BalancedReaction.reactants`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.BalancedReaction.reactants)


        * [`ComputedReaction`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.ComputedReaction)


            * [`ComputedReaction.all_entries`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.ComputedReaction.all_entries)


            * [`ComputedReaction.as_dict()`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.ComputedReaction.as_dict)


            * [`ComputedReaction.calculated_reaction_energy`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.ComputedReaction.calculated_reaction_energy)


            * [`ComputedReaction.calculated_reaction_energy_uncertainty`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.ComputedReaction.calculated_reaction_energy_uncertainty)


            * [`ComputedReaction.from_dict()`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.ComputedReaction.from_dict)


        * [`Reaction`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.Reaction)


            * [`Reaction._balance_coeffs()`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.Reaction._balance_coeffs)


            * [`Reaction.as_dict()`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.Reaction.as_dict)


            * [`Reaction.copy()`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.Reaction.copy)


            * [`Reaction.from_dict()`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.Reaction.from_dict)


        * [`ReactionError`](pymatgen.analysis.md#pymatgen.analysis.reaction_calculator.ReactionError)


    * [pymatgen.analysis.structure_analyzer module](pymatgen.analysis.md#module-pymatgen.analysis.structure_analyzer)


        * [`OxideType`](pymatgen.analysis.md#pymatgen.analysis.structure_analyzer.OxideType)


            * [`OxideType.parse_oxide()`](pymatgen.analysis.md#pymatgen.analysis.structure_analyzer.OxideType.parse_oxide)


        * [`RelaxationAnalyzer`](pymatgen.analysis.md#pymatgen.analysis.structure_analyzer.RelaxationAnalyzer)


            * [`RelaxationAnalyzer.get_percentage_bond_dist_changes()`](pymatgen.analysis.md#pymatgen.analysis.structure_analyzer.RelaxationAnalyzer.get_percentage_bond_dist_changes)


            * [`RelaxationAnalyzer.get_percentage_lattice_parameter_changes()`](pymatgen.analysis.md#pymatgen.analysis.structure_analyzer.RelaxationAnalyzer.get_percentage_lattice_parameter_changes)


            * [`RelaxationAnalyzer.get_percentage_volume_change()`](pymatgen.analysis.md#pymatgen.analysis.structure_analyzer.RelaxationAnalyzer.get_percentage_volume_change)


        * [`VoronoiAnalyzer`](pymatgen.analysis.md#pymatgen.analysis.structure_analyzer.VoronoiAnalyzer)


            * [`VoronoiAnalyzer.analyze()`](pymatgen.analysis.md#pymatgen.analysis.structure_analyzer.VoronoiAnalyzer.analyze)


            * [`VoronoiAnalyzer.analyze_structures()`](pymatgen.analysis.md#pymatgen.analysis.structure_analyzer.VoronoiAnalyzer.analyze_structures)


            * [`VoronoiAnalyzer.plot_vor_analysis()`](pymatgen.analysis.md#pymatgen.analysis.structure_analyzer.VoronoiAnalyzer.plot_vor_analysis)


        * [`VoronoiConnectivity`](pymatgen.analysis.md#pymatgen.analysis.structure_analyzer.VoronoiConnectivity)


            * [`VoronoiConnectivity.connectivity_array`](pymatgen.analysis.md#pymatgen.analysis.structure_analyzer.VoronoiConnectivity.connectivity_array)


            * [`VoronoiConnectivity.get_connections()`](pymatgen.analysis.md#pymatgen.analysis.structure_analyzer.VoronoiConnectivity.get_connections)


            * [`VoronoiConnectivity.get_sitej()`](pymatgen.analysis.md#pymatgen.analysis.structure_analyzer.VoronoiConnectivity.get_sitej)


            * [`VoronoiConnectivity.max_connectivity`](pymatgen.analysis.md#pymatgen.analysis.structure_analyzer.VoronoiConnectivity.max_connectivity)


        * [`average_coordination_number()`](pymatgen.analysis.md#pymatgen.analysis.structure_analyzer.average_coordination_number)


        * [`contains_peroxide()`](pymatgen.analysis.md#pymatgen.analysis.structure_analyzer.contains_peroxide)


        * [`get_max_bond_lengths()`](pymatgen.analysis.md#pymatgen.analysis.structure_analyzer.get_max_bond_lengths)


        * [`oxide_type()`](pymatgen.analysis.md#pymatgen.analysis.structure_analyzer.oxide_type)


        * [`solid_angle()`](pymatgen.analysis.md#pymatgen.analysis.structure_analyzer.solid_angle)


        * [`sulfide_type()`](pymatgen.analysis.md#pymatgen.analysis.structure_analyzer.sulfide_type)


    * [pymatgen.analysis.structure_matcher module](pymatgen.analysis.md#module-pymatgen.analysis.structure_matcher)


        * [`AbstractComparator`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.AbstractComparator)


            * [`AbstractComparator._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.AbstractComparator._abc_impl)


            * [`AbstractComparator.are_equal()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.AbstractComparator.are_equal)


            * [`AbstractComparator.as_dict()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.AbstractComparator.as_dict)


            * [`AbstractComparator.from_dict()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.AbstractComparator.from_dict)


            * [`AbstractComparator.get_hash()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.AbstractComparator.get_hash)


        * [`ElementComparator`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.ElementComparator)


            * [`ElementComparator._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.ElementComparator._abc_impl)


            * [`ElementComparator.are_equal()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.ElementComparator.are_equal)


            * [`ElementComparator.get_hash()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.ElementComparator.get_hash)


        * [`FrameworkComparator`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.FrameworkComparator)


            * [`FrameworkComparator._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.FrameworkComparator._abc_impl)


            * [`FrameworkComparator.are_equal()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.FrameworkComparator.are_equal)


            * [`FrameworkComparator.get_hash()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.FrameworkComparator.get_hash)


        * [`OccupancyComparator`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.OccupancyComparator)


            * [`OccupancyComparator._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.OccupancyComparator._abc_impl)


            * [`OccupancyComparator.are_equal()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.OccupancyComparator.are_equal)


            * [`OccupancyComparator.get_hash()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.OccupancyComparator.get_hash)


        * [`OrderDisorderElementComparator`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.OrderDisorderElementComparator)


            * [`OrderDisorderElementComparator._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.OrderDisorderElementComparator._abc_impl)


            * [`OrderDisorderElementComparator.are_equal()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.OrderDisorderElementComparator.are_equal)


            * [`OrderDisorderElementComparator.get_hash()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.OrderDisorderElementComparator.get_hash)


        * [`SpeciesComparator`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.SpeciesComparator)


            * [`SpeciesComparator._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.SpeciesComparator._abc_impl)


            * [`SpeciesComparator.are_equal()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.SpeciesComparator.are_equal)


            * [`SpeciesComparator.get_hash()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.SpeciesComparator.get_hash)


        * [`SpinComparator`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.SpinComparator)


            * [`SpinComparator._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.SpinComparator._abc_impl)


            * [`SpinComparator.are_equal()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.SpinComparator.are_equal)


            * [`SpinComparator.get_hash()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.SpinComparator.get_hash)


        * [`StructureMatcher`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.StructureMatcher)


            * [`StructureMatcher._anonymous_match()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.StructureMatcher._anonymous_match)


            * [`StructureMatcher._cart_dists()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.StructureMatcher._cart_dists)


            * [`StructureMatcher._cmp_fstruct()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.StructureMatcher._cmp_fstruct)


            * [`StructureMatcher._get_lattices()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.StructureMatcher._get_lattices)


            * [`StructureMatcher._get_mask()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.StructureMatcher._get_mask)


            * [`StructureMatcher._get_reduced_structure()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.StructureMatcher._get_reduced_structure)


            * [`StructureMatcher._get_supercell_size()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.StructureMatcher._get_supercell_size)


            * [`StructureMatcher._get_supercells()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.StructureMatcher._get_supercells)


            * [`StructureMatcher._match()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.StructureMatcher._match)


            * [`StructureMatcher._preprocess()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.StructureMatcher._preprocess)


            * [`StructureMatcher._process_species()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.StructureMatcher._process_species)


            * [`StructureMatcher._strict_match()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.StructureMatcher._strict_match)


            * [`StructureMatcher.as_dict()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.StructureMatcher.as_dict)


            * [`StructureMatcher.fit()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.StructureMatcher.fit)


            * [`StructureMatcher.fit_anonymous()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.StructureMatcher.fit_anonymous)


            * [`StructureMatcher.from_dict()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.StructureMatcher.from_dict)


            * [`StructureMatcher.get_all_anonymous_mappings()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.StructureMatcher.get_all_anonymous_mappings)


            * [`StructureMatcher.get_best_electronegativity_anonymous_mapping()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.StructureMatcher.get_best_electronegativity_anonymous_mapping)


            * [`StructureMatcher.get_mapping()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.StructureMatcher.get_mapping)


            * [`StructureMatcher.get_rms_anonymous()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.StructureMatcher.get_rms_anonymous)


            * [`StructureMatcher.get_rms_dist()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.StructureMatcher.get_rms_dist)


            * [`StructureMatcher.get_s2_like_s1()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.StructureMatcher.get_s2_like_s1)


            * [`StructureMatcher.get_supercell_matrix()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.StructureMatcher.get_supercell_matrix)


            * [`StructureMatcher.get_transformation()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.StructureMatcher.get_transformation)


            * [`StructureMatcher.group_structures()`](pymatgen.analysis.md#pymatgen.analysis.structure_matcher.StructureMatcher.group_structures)


    * [pymatgen.analysis.surface_analysis module](pymatgen.analysis.md#module-pymatgen.analysis.surface_analysis)


        * [`NanoscaleStability`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.NanoscaleStability)


            * [`NanoscaleStability.se_analyzers`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.NanoscaleStability.se_analyzers)


            * [`NanoscaleStability.symprec`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.NanoscaleStability.symprec)


            * [`NanoscaleStability.bulk_gform()`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.NanoscaleStability.bulk_gform)


            * [`NanoscaleStability.plot_all_stability_map()`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.NanoscaleStability.plot_all_stability_map)


            * [`NanoscaleStability.plot_one_stability_map()`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.NanoscaleStability.plot_one_stability_map)


            * [`NanoscaleStability.scaled_wulff()`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.NanoscaleStability.scaled_wulff)


            * [`NanoscaleStability.solve_equilibrium_point()`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.NanoscaleStability.solve_equilibrium_point)


            * [`NanoscaleStability.wulff_gform_and_r()`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.NanoscaleStability.wulff_gform_and_r)


        * [`SlabEntry`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SlabEntry)


            * [`SlabEntry.miller_index`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SlabEntry.miller_index)


            * [`SlabEntry.label`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SlabEntry.label)


            * [`SlabEntry.adsorbates`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SlabEntry.adsorbates)


            * [`SlabEntry.clean_entry`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SlabEntry.clean_entry)


            * [`SlabEntry.ads_entries_dict`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SlabEntry.ads_entries_dict)


            * [`SlabEntry.Nads_in_slab`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SlabEntry.Nads_in_slab)


            * [`SlabEntry.Nsurfs_ads_in_slab`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SlabEntry.Nsurfs_ads_in_slab)


            * [`SlabEntry._abc_impl`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SlabEntry._abc_impl)


            * [`SlabEntry.as_dict()`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SlabEntry.as_dict)


            * [`SlabEntry.cleaned_up_slab`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SlabEntry.cleaned_up_slab)


            * [`SlabEntry.create_slab_label`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SlabEntry.create_slab_label)


            * [`SlabEntry.from_computed_structure_entry()`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SlabEntry.from_computed_structure_entry)


            * [`SlabEntry.from_dict()`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SlabEntry.from_dict)


            * [`SlabEntry.get_monolayer`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SlabEntry.get_monolayer)


            * [`SlabEntry.get_unit_primitive_area`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SlabEntry.get_unit_primitive_area)


            * [`SlabEntry.gibbs_binding_energy()`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SlabEntry.gibbs_binding_energy)


            * [`SlabEntry.surface_area`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SlabEntry.surface_area)


            * [`SlabEntry.surface_energy()`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SlabEntry.surface_energy)


        * [`SurfaceEnergyPlotter`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SurfaceEnergyPlotter)


            * [`SurfaceEnergyPlotter.all_slab_entries`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SurfaceEnergyPlotter.all_slab_entries)


            * [`SurfaceEnergyPlotter.color_dict`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SurfaceEnergyPlotter.color_dict)


            * [`SurfaceEnergyPlotter.ucell_entry`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SurfaceEnergyPlotter.ucell_entry)


            * [`SurfaceEnergyPlotter.ref_entries`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SurfaceEnergyPlotter.ref_entries)


            * [`SurfaceEnergyPlotter.facet_color_dict`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SurfaceEnergyPlotter.facet_color_dict)


            * [`SurfaceEnergyPlotter.BE_vs_clean_SE()`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SurfaceEnergyPlotter.BE_vs_clean_SE)


            * [`SurfaceEnergyPlotter.area_frac_vs_chempot_plot()`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SurfaceEnergyPlotter.area_frac_vs_chempot_plot)


            * [`SurfaceEnergyPlotter.chempot_plot_addons()`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SurfaceEnergyPlotter.chempot_plot_addons)


            * [`SurfaceEnergyPlotter.chempot_vs_gamma()`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SurfaceEnergyPlotter.chempot_vs_gamma)


            * [`SurfaceEnergyPlotter.chempot_vs_gamma_plot_one()`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SurfaceEnergyPlotter.chempot_vs_gamma_plot_one)


            * [`SurfaceEnergyPlotter.color_palette_dict()`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SurfaceEnergyPlotter.color_palette_dict)


            * [`SurfaceEnergyPlotter.get_stable_entry_at_u()`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SurfaceEnergyPlotter.get_stable_entry_at_u)


            * [`SurfaceEnergyPlotter.get_surface_equilibrium()`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SurfaceEnergyPlotter.get_surface_equilibrium)


            * [`SurfaceEnergyPlotter.monolayer_vs_BE()`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SurfaceEnergyPlotter.monolayer_vs_BE)


            * [`SurfaceEnergyPlotter.set_all_variables()`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SurfaceEnergyPlotter.set_all_variables)


            * [`SurfaceEnergyPlotter.stable_u_range_dict()`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SurfaceEnergyPlotter.stable_u_range_dict)


            * [`SurfaceEnergyPlotter.surface_chempot_range_map()`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SurfaceEnergyPlotter.surface_chempot_range_map)


            * [`SurfaceEnergyPlotter.wulff_from_chempot()`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.SurfaceEnergyPlotter.wulff_from_chempot)


        * [`WorkFunctionAnalyzer`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.WorkFunctionAnalyzer)


            * [`WorkFunctionAnalyzer.efermi`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.WorkFunctionAnalyzer.efermi)


            * [`WorkFunctionAnalyzer.locpot_along_c`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.WorkFunctionAnalyzer.locpot_along_c)


            * [`WorkFunctionAnalyzer.vacuum_locpot`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.WorkFunctionAnalyzer.vacuum_locpot)


            * [`WorkFunctionAnalyzer.work_function`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.WorkFunctionAnalyzer.work_function)


            * [`WorkFunctionAnalyzer.slab`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.WorkFunctionAnalyzer.slab)


            * [`WorkFunctionAnalyzer.along_c`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.WorkFunctionAnalyzer.along_c)


            * [`WorkFunctionAnalyzer.ave_locpot`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.WorkFunctionAnalyzer.ave_locpot)


            * [`WorkFunctionAnalyzer.sorted_sites`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.WorkFunctionAnalyzer.sorted_sites)


            * [`WorkFunctionAnalyzer.ave_bulk_p`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.WorkFunctionAnalyzer.ave_bulk_p)


            * [`WorkFunctionAnalyzer.from_files()`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.WorkFunctionAnalyzer.from_files)


            * [`WorkFunctionAnalyzer.get_labels()`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.WorkFunctionAnalyzer.get_labels)


            * [`WorkFunctionAnalyzer.get_locpot_along_slab_plot()`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.WorkFunctionAnalyzer.get_locpot_along_slab_plot)


            * [`WorkFunctionAnalyzer.is_converged()`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.WorkFunctionAnalyzer.is_converged)


        * [`entry_dict_from_list()`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.entry_dict_from_list)


        * [`sub_chempots()`](pymatgen.analysis.md#pymatgen.analysis.surface_analysis.sub_chempots)


    * [pymatgen.analysis.thermochemistry module](pymatgen.analysis.md#module-pymatgen.analysis.thermochemistry)


        * [`ThermoData`](pymatgen.analysis.md#pymatgen.analysis.thermochemistry.ThermoData)


            * [`ThermoData.as_dict()`](pymatgen.analysis.md#pymatgen.analysis.thermochemistry.ThermoData.as_dict)


            * [`ThermoData.from_dict()`](pymatgen.analysis.md#pymatgen.analysis.thermochemistry.ThermoData.from_dict)


    * [pymatgen.analysis.transition_state module](pymatgen.analysis.md#module-pymatgen.analysis.transition_state)


        * [`NEBAnalysis`](pymatgen.analysis.md#pymatgen.analysis.transition_state.NEBAnalysis)


            * [`NEBAnalysis.as_dict()`](pymatgen.analysis.md#pymatgen.analysis.transition_state.NEBAnalysis.as_dict)


            * [`NEBAnalysis.from_dir()`](pymatgen.analysis.md#pymatgen.analysis.transition_state.NEBAnalysis.from_dir)


            * [`NEBAnalysis.from_outcars()`](pymatgen.analysis.md#pymatgen.analysis.transition_state.NEBAnalysis.from_outcars)


            * [`NEBAnalysis.get_extrema()`](pymatgen.analysis.md#pymatgen.analysis.transition_state.NEBAnalysis.get_extrema)


            * [`NEBAnalysis.get_plot()`](pymatgen.analysis.md#pymatgen.analysis.transition_state.NEBAnalysis.get_plot)


            * [`NEBAnalysis.setup_spline()`](pymatgen.analysis.md#pymatgen.analysis.transition_state.NEBAnalysis.setup_spline)


        * [`combine_neb_plots()`](pymatgen.analysis.md#pymatgen.analysis.transition_state.combine_neb_plots)


    * [pymatgen.analysis.wulff module](pymatgen.analysis.md#module-pymatgen.analysis.wulff)


        * [`WulffFacet`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffFacet)


        * [`WulffShape`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape)


            * [`WulffShape.debug`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.debug)


            * [`WulffShape.alpha`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.alpha)


            * [`WulffShape.color_set`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.color_set)


            * [`WulffShape.grid_off`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.grid_off)


            * [`WulffShape.axis_off`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.axis_off)


            * [`WulffShape.show_area`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.show_area)


            * [`WulffShape.off_color`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.off_color)


            * [`WulffShape.structure`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.structure)


            * [`WulffShape.miller_list`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.miller_list)


            * [`WulffShape.hkl_list`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.hkl_list)


            * [`WulffShape.e_surf_list`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.e_surf_list)


            * [`WulffShape.lattice`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.lattice)


            * [`WulffShape.facets`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.facets)


            * [`WulffShape.dual_cv_simp`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.dual_cv_simp)


            * [`WulffShape.wulff_pt_list`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.wulff_pt_list)


            * [`WulffShape.wulff_cv_simp`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.wulff_cv_simp)


            * [`WulffShape.on_wulff`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.on_wulff)


            * [`WulffShape.color_area`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.color_area)


            * [`WulffShape.miller_area`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.miller_area)


            * [`WulffShape._get_all_miller_e()`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape._get_all_miller_e)


            * [`WulffShape._get_azimuth_elev()`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape._get_azimuth_elev)


            * [`WulffShape._get_colors()`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape._get_colors)


            * [`WulffShape._get_cross_pt_dual_simp()`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape._get_cross_pt_dual_simp)


            * [`WulffShape._get_simpx_plane()`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape._get_simpx_plane)


            * [`WulffShape.anisotropy`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.anisotropy)


            * [`WulffShape.area_fraction_dict`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.area_fraction_dict)


            * [`WulffShape.effective_radius`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.effective_radius)


            * [`WulffShape.get_line_in_facet()`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.get_line_in_facet)


            * [`WulffShape.get_plot()`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.get_plot)


            * [`WulffShape.get_plotly()`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.get_plotly)


            * [`WulffShape.miller_area_dict`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.miller_area_dict)


            * [`WulffShape.miller_energy_dict`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.miller_energy_dict)


            * [`WulffShape.shape_factor`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.shape_factor)


            * [`WulffShape.show()`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.show)


            * [`WulffShape.surface_area`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.surface_area)


            * [`WulffShape.tot_corner_sites`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.tot_corner_sites)


            * [`WulffShape.tot_edges`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.tot_edges)


            * [`WulffShape.total_surface_energy`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.total_surface_energy)


            * [`WulffShape.volume`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.volume)


            * [`WulffShape.weighted_surface_energy`](pymatgen.analysis.md#pymatgen.analysis.wulff.WulffShape.weighted_surface_energy)


        * [`get_tri_area()`](pymatgen.analysis.md#pymatgen.analysis.wulff.get_tri_area)


        * [`hkl_tuple_to_str()`](pymatgen.analysis.md#pymatgen.analysis.wulff.hkl_tuple_to_str)


    * [pymatgen.analysis.xps module](pymatgen.analysis.md#module-pymatgen.analysis.xps)


        * [`XPS`](pymatgen.analysis.md#pymatgen.analysis.xps.XPS)


            * [`XPS.XLABEL`](pymatgen.analysis.md#pymatgen.analysis.xps.XPS.XLABEL)


            * [`XPS.YLABEL`](pymatgen.analysis.md#pymatgen.analysis.xps.XPS.YLABEL)


            * [`XPS.from_dos()`](pymatgen.analysis.md#pymatgen.analysis.xps.XPS.from_dos)


        * [`_load_cross_sections()`](pymatgen.analysis.md#pymatgen.analysis.xps._load_cross_sections)


* [pymatgen.apps package](pymatgen.apps.md)


    * [Subpackages](pymatgen.apps.md#subpackages)


        * [pymatgen.apps.battery package](pymatgen.apps.battery.md)




            * [pymatgen.apps.battery.analyzer module](pymatgen.apps.battery.md#module-pymatgen.apps.battery.analyzer)


                * [`BatteryAnalyzer`](pymatgen.apps.battery.md#pymatgen.apps.battery.analyzer.BatteryAnalyzer)


                    * [`BatteryAnalyzer._get_int_removals_helper()`](pymatgen.apps.battery.md#pymatgen.apps.battery.analyzer.BatteryAnalyzer._get_int_removals_helper)


                    * [`BatteryAnalyzer._get_max_cap_ah()`](pymatgen.apps.battery.md#pymatgen.apps.battery.analyzer.BatteryAnalyzer._get_max_cap_ah)


                    * [`BatteryAnalyzer.get_max_capgrav()`](pymatgen.apps.battery.md#pymatgen.apps.battery.analyzer.BatteryAnalyzer.get_max_capgrav)


                    * [`BatteryAnalyzer.get_max_capvol()`](pymatgen.apps.battery.md#pymatgen.apps.battery.analyzer.BatteryAnalyzer.get_max_capvol)


                    * [`BatteryAnalyzer.get_removals_int_oxid()`](pymatgen.apps.battery.md#pymatgen.apps.battery.analyzer.BatteryAnalyzer.get_removals_int_oxid)


                    * [`BatteryAnalyzer.max_ion_insertion`](pymatgen.apps.battery.md#pymatgen.apps.battery.analyzer.BatteryAnalyzer.max_ion_insertion)


                    * [`BatteryAnalyzer.max_ion_removal`](pymatgen.apps.battery.md#pymatgen.apps.battery.analyzer.BatteryAnalyzer.max_ion_removal)


                * [`is_redox_active_intercalation()`](pymatgen.apps.battery.md#pymatgen.apps.battery.analyzer.is_redox_active_intercalation)


            * [pymatgen.apps.battery.battery_abc module](pymatgen.apps.battery.md#module-pymatgen.apps.battery.battery_abc)


                * [`AbstractElectrode`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractElectrode)


                    * [`AbstractElectrode.voltage_pairs`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractElectrode.voltage_pairs)


                    * [`AbstractElectrode.working_ion`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractElectrode.working_ion)


                    * [`AbstractElectrode.working_ion_entry`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractElectrode.working_ion_entry)


                    * [`AbstractElectrode.framework_formula`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractElectrode.framework_formula)


                    * [`AbstractElectrode._abc_impl`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractElectrode._abc_impl)


                    * [`AbstractElectrode._select_in_voltage_range()`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractElectrode._select_in_voltage_range)


                    * [`AbstractElectrode.framework`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractElectrode.framework)


                    * [`AbstractElectrode.framework_formula`](pymatgen.apps.battery.md#id0)


                    * [`AbstractElectrode.get_average_voltage()`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractElectrode.get_average_voltage)


                    * [`AbstractElectrode.get_capacity_grav()`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractElectrode.get_capacity_grav)


                    * [`AbstractElectrode.get_capacity_vol()`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractElectrode.get_capacity_vol)


                    * [`AbstractElectrode.get_energy_density()`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractElectrode.get_energy_density)


                    * [`AbstractElectrode.get_specific_energy()`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractElectrode.get_specific_energy)


                    * [`AbstractElectrode.get_sub_electrodes()`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractElectrode.get_sub_electrodes)


                    * [`AbstractElectrode.get_summary_dict()`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractElectrode.get_summary_dict)


                    * [`AbstractElectrode.max_delta_volume`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractElectrode.max_delta_volume)


                    * [`AbstractElectrode.max_voltage`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractElectrode.max_voltage)


                    * [`AbstractElectrode.max_voltage_step`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractElectrode.max_voltage_step)


                    * [`AbstractElectrode.min_voltage`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractElectrode.min_voltage)


                    * [`AbstractElectrode.normalization_mass`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractElectrode.normalization_mass)


                    * [`AbstractElectrode.normalization_volume`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractElectrode.normalization_volume)


                    * [`AbstractElectrode.num_steps`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractElectrode.num_steps)


                    * [`AbstractElectrode.voltage_pairs`](pymatgen.apps.battery.md#id1)


                    * [`AbstractElectrode.working_ion`](pymatgen.apps.battery.md#id2)


                    * [`AbstractElectrode.working_ion_entry`](pymatgen.apps.battery.md#id3)


                    * [`AbstractElectrode.x_charge`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractElectrode.x_charge)


                    * [`AbstractElectrode.x_discharge`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractElectrode.x_discharge)


                * [`AbstractVoltagePair`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractVoltagePair)


                    * [`AbstractVoltagePair.voltage`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractVoltagePair.voltage)


                    * [`AbstractVoltagePair.mAh`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractVoltagePair.mAh)


                    * [`AbstractVoltagePair.mass_charge`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractVoltagePair.mass_charge)


                    * [`AbstractVoltagePair.mass_discharge`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractVoltagePair.mass_discharge)


                    * [`AbstractVoltagePair.vol_charge`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractVoltagePair.vol_charge)


                    * [`AbstractVoltagePair.vol_discharge`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractVoltagePair.vol_discharge)


                    * [`AbstractVoltagePair.frac_charge`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractVoltagePair.frac_charge)


                    * [`AbstractVoltagePair.frac_discharge`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractVoltagePair.frac_discharge)


                    * [`AbstractVoltagePair.working_ion_entry`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractVoltagePair.working_ion_entry)


                    * [`AbstractVoltagePair.framework_formula`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractVoltagePair.framework_formula)


                    * [`AbstractVoltagePair.frac_charge`](pymatgen.apps.battery.md#id4)


                    * [`AbstractVoltagePair.frac_discharge`](pymatgen.apps.battery.md#id5)


                    * [`AbstractVoltagePair.framework`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractVoltagePair.framework)


                    * [`AbstractVoltagePair.framework_formula`](pymatgen.apps.battery.md#id6)


                    * [`AbstractVoltagePair.mAh`](pymatgen.apps.battery.md#id7)


                    * [`AbstractVoltagePair.mass_charge`](pymatgen.apps.battery.md#id8)


                    * [`AbstractVoltagePair.mass_discharge`](pymatgen.apps.battery.md#id9)


                    * [`AbstractVoltagePair.vol_charge`](pymatgen.apps.battery.md#id10)


                    * [`AbstractVoltagePair.vol_discharge`](pymatgen.apps.battery.md#id11)


                    * [`AbstractVoltagePair.voltage`](pymatgen.apps.battery.md#id12)


                    * [`AbstractVoltagePair.working_ion`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractVoltagePair.working_ion)


                    * [`AbstractVoltagePair.working_ion_entry`](pymatgen.apps.battery.md#id13)


                    * [`AbstractVoltagePair.x_charge`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractVoltagePair.x_charge)


                    * [`AbstractVoltagePair.x_discharge`](pymatgen.apps.battery.md#pymatgen.apps.battery.battery_abc.AbstractVoltagePair.x_discharge)


            * [pymatgen.apps.battery.conversion_battery module](pymatgen.apps.battery.md#module-pymatgen.apps.battery.conversion_battery)


                * [`ConversionElectrode`](pymatgen.apps.battery.md#pymatgen.apps.battery.conversion_battery.ConversionElectrode)


                    * [`ConversionElectrode._abc_impl`](pymatgen.apps.battery.md#pymatgen.apps.battery.conversion_battery.ConversionElectrode._abc_impl)


                    * [`ConversionElectrode.from_composition_and_entries()`](pymatgen.apps.battery.md#pymatgen.apps.battery.conversion_battery.ConversionElectrode.from_composition_and_entries)


                    * [`ConversionElectrode.from_composition_and_pd()`](pymatgen.apps.battery.md#pymatgen.apps.battery.conversion_battery.ConversionElectrode.from_composition_and_pd)


                    * [`ConversionElectrode.get_sub_electrodes()`](pymatgen.apps.battery.md#pymatgen.apps.battery.conversion_battery.ConversionElectrode.get_sub_electrodes)


                    * [`ConversionElectrode.get_summary_dict()`](pymatgen.apps.battery.md#pymatgen.apps.battery.conversion_battery.ConversionElectrode.get_summary_dict)


                    * [`ConversionElectrode.initial_comp`](pymatgen.apps.battery.md#pymatgen.apps.battery.conversion_battery.ConversionElectrode.initial_comp)


                    * [`ConversionElectrode.initial_comp_formula`](pymatgen.apps.battery.md#pymatgen.apps.battery.conversion_battery.ConversionElectrode.initial_comp_formula)


                    * [`ConversionElectrode.is_super_electrode()`](pymatgen.apps.battery.md#pymatgen.apps.battery.conversion_battery.ConversionElectrode.is_super_electrode)


                * [`ConversionVoltagePair`](pymatgen.apps.battery.md#pymatgen.apps.battery.conversion_battery.ConversionVoltagePair)


                    * [`ConversionVoltagePair.rxn`](pymatgen.apps.battery.md#pymatgen.apps.battery.conversion_battery.ConversionVoltagePair.rxn)


                    * [`ConversionVoltagePair.voltage`](pymatgen.apps.battery.md#pymatgen.apps.battery.conversion_battery.ConversionVoltagePair.voltage)


                    * [`ConversionVoltagePair.mAh`](pymatgen.apps.battery.md#pymatgen.apps.battery.conversion_battery.ConversionVoltagePair.mAh)


                    * [`ConversionVoltagePair.vol_charge`](pymatgen.apps.battery.md#pymatgen.apps.battery.conversion_battery.ConversionVoltagePair.vol_charge)


                    * [`ConversionVoltagePair.vol_discharge`](pymatgen.apps.battery.md#pymatgen.apps.battery.conversion_battery.ConversionVoltagePair.vol_discharge)


                    * [`ConversionVoltagePair.mass_charge`](pymatgen.apps.battery.md#pymatgen.apps.battery.conversion_battery.ConversionVoltagePair.mass_charge)


                    * [`ConversionVoltagePair.mass_discharge`](pymatgen.apps.battery.md#pymatgen.apps.battery.conversion_battery.ConversionVoltagePair.mass_discharge)


                    * [`ConversionVoltagePair.frac_charge`](pymatgen.apps.battery.md#pymatgen.apps.battery.conversion_battery.ConversionVoltagePair.frac_charge)


                    * [`ConversionVoltagePair.frac_discharge`](pymatgen.apps.battery.md#pymatgen.apps.battery.conversion_battery.ConversionVoltagePair.frac_discharge)


                    * [`ConversionVoltagePair.entries_charge`](pymatgen.apps.battery.md#pymatgen.apps.battery.conversion_battery.ConversionVoltagePair.entries_charge)


                    * [`ConversionVoltagePair.entries_discharge`](pymatgen.apps.battery.md#pymatgen.apps.battery.conversion_battery.ConversionVoltagePair.entries_discharge)


                    * [`ConversionVoltagePair.working_ion_entry`](pymatgen.apps.battery.md#pymatgen.apps.battery.conversion_battery.ConversionVoltagePair.working_ion_entry)


                    * [`ConversionVoltagePair.entries_charge`](pymatgen.apps.battery.md#id14)


                    * [`ConversionVoltagePair.entries_discharge`](pymatgen.apps.battery.md#id15)


                    * [`ConversionVoltagePair.from_steps()`](pymatgen.apps.battery.md#pymatgen.apps.battery.conversion_battery.ConversionVoltagePair.from_steps)


                    * [`ConversionVoltagePair.rxn`](pymatgen.apps.battery.md#id16)


            * [pymatgen.apps.battery.insertion_battery module](pymatgen.apps.battery.md#module-pymatgen.apps.battery.insertion_battery)


                * [`InsertionElectrode`](pymatgen.apps.battery.md#pymatgen.apps.battery.insertion_battery.InsertionElectrode)


                    * [`InsertionElectrode._abc_impl`](pymatgen.apps.battery.md#pymatgen.apps.battery.insertion_battery.InsertionElectrode._abc_impl)


                    * [`InsertionElectrode.as_dict_legacy()`](pymatgen.apps.battery.md#pymatgen.apps.battery.insertion_battery.InsertionElectrode.as_dict_legacy)


                    * [`InsertionElectrode.from_dict_legacy()`](pymatgen.apps.battery.md#pymatgen.apps.battery.insertion_battery.InsertionElectrode.from_dict_legacy)


                    * [`InsertionElectrode.from_entries()`](pymatgen.apps.battery.md#pymatgen.apps.battery.insertion_battery.InsertionElectrode.from_entries)


                    * [`InsertionElectrode.fully_charged_entry`](pymatgen.apps.battery.md#pymatgen.apps.battery.insertion_battery.InsertionElectrode.fully_charged_entry)


                    * [`InsertionElectrode.fully_discharged_entry`](pymatgen.apps.battery.md#pymatgen.apps.battery.insertion_battery.InsertionElectrode.fully_discharged_entry)


                    * [`InsertionElectrode.get_all_entries()`](pymatgen.apps.battery.md#pymatgen.apps.battery.insertion_battery.InsertionElectrode.get_all_entries)


                    * [`InsertionElectrode.get_max_instability()`](pymatgen.apps.battery.md#pymatgen.apps.battery.insertion_battery.InsertionElectrode.get_max_instability)


                    * [`InsertionElectrode.get_max_muO2()`](pymatgen.apps.battery.md#pymatgen.apps.battery.insertion_battery.InsertionElectrode.get_max_muO2)


                    * [`InsertionElectrode.get_min_instability()`](pymatgen.apps.battery.md#pymatgen.apps.battery.insertion_battery.InsertionElectrode.get_min_instability)


                    * [`InsertionElectrode.get_min_muO2()`](pymatgen.apps.battery.md#pymatgen.apps.battery.insertion_battery.InsertionElectrode.get_min_muO2)


                    * [`InsertionElectrode.get_stable_entries()`](pymatgen.apps.battery.md#pymatgen.apps.battery.insertion_battery.InsertionElectrode.get_stable_entries)


                    * [`InsertionElectrode.get_sub_electrodes()`](pymatgen.apps.battery.md#pymatgen.apps.battery.insertion_battery.InsertionElectrode.get_sub_electrodes)


                    * [`InsertionElectrode.get_summary_dict()`](pymatgen.apps.battery.md#pymatgen.apps.battery.insertion_battery.InsertionElectrode.get_summary_dict)


                    * [`InsertionElectrode.get_unstable_entries()`](pymatgen.apps.battery.md#pymatgen.apps.battery.insertion_battery.InsertionElectrode.get_unstable_entries)


                    * [`InsertionElectrode.stable_entries`](pymatgen.apps.battery.md#pymatgen.apps.battery.insertion_battery.InsertionElectrode.stable_entries)


                    * [`InsertionElectrode.unstable_entries`](pymatgen.apps.battery.md#pymatgen.apps.battery.insertion_battery.InsertionElectrode.unstable_entries)


                * [`InsertionVoltagePair`](pymatgen.apps.battery.md#pymatgen.apps.battery.insertion_battery.InsertionVoltagePair)


                    * [`InsertionVoltagePair.entry_charge`](pymatgen.apps.battery.md#pymatgen.apps.battery.insertion_battery.InsertionVoltagePair.entry_charge)


                    * [`InsertionVoltagePair.entry_discharge`](pymatgen.apps.battery.md#pymatgen.apps.battery.insertion_battery.InsertionVoltagePair.entry_discharge)


                    * [`InsertionVoltagePair.from_entries()`](pymatgen.apps.battery.md#pymatgen.apps.battery.insertion_battery.InsertionVoltagePair.from_entries)


            * [pymatgen.apps.battery.plotter module](pymatgen.apps.battery.md#module-pymatgen.apps.battery.plotter)


                * [`VoltageProfilePlotter`](pymatgen.apps.battery.md#pymatgen.apps.battery.plotter.VoltageProfilePlotter)


                    * [`VoltageProfilePlotter._choose_best_x_label()`](pymatgen.apps.battery.md#pymatgen.apps.battery.plotter.VoltageProfilePlotter._choose_best_x_label)


                    * [`VoltageProfilePlotter.add_electrode()`](pymatgen.apps.battery.md#pymatgen.apps.battery.plotter.VoltageProfilePlotter.add_electrode)


                    * [`VoltageProfilePlotter.get_plot()`](pymatgen.apps.battery.md#pymatgen.apps.battery.plotter.VoltageProfilePlotter.get_plot)


                    * [`VoltageProfilePlotter.get_plot_data()`](pymatgen.apps.battery.md#pymatgen.apps.battery.plotter.VoltageProfilePlotter.get_plot_data)


                    * [`VoltageProfilePlotter.get_plotly_figure()`](pymatgen.apps.battery.md#pymatgen.apps.battery.plotter.VoltageProfilePlotter.get_plotly_figure)


                    * [`VoltageProfilePlotter.save()`](pymatgen.apps.battery.md#pymatgen.apps.battery.plotter.VoltageProfilePlotter.save)


                    * [`VoltageProfilePlotter.show()`](pymatgen.apps.battery.md#pymatgen.apps.battery.plotter.VoltageProfilePlotter.show)


        * [pymatgen.apps.borg package](pymatgen.apps.borg.md)




            * [pymatgen.apps.borg.hive module](pymatgen.apps.borg.md#module-pymatgen.apps.borg.hive)


                * [`AbstractDrone`](pymatgen.apps.borg.md#pymatgen.apps.borg.hive.AbstractDrone)


                    * [`AbstractDrone._abc_impl`](pymatgen.apps.borg.md#pymatgen.apps.borg.hive.AbstractDrone._abc_impl)


                    * [`AbstractDrone.assimilate()`](pymatgen.apps.borg.md#pymatgen.apps.borg.hive.AbstractDrone.assimilate)


                    * [`AbstractDrone.get_valid_paths()`](pymatgen.apps.borg.md#pymatgen.apps.borg.hive.AbstractDrone.get_valid_paths)


                * [`GaussianToComputedEntryDrone`](pymatgen.apps.borg.md#pymatgen.apps.borg.hive.GaussianToComputedEntryDrone)


                    * [`GaussianToComputedEntryDrone._abc_impl`](pymatgen.apps.borg.md#pymatgen.apps.borg.hive.GaussianToComputedEntryDrone._abc_impl)


                    * [`GaussianToComputedEntryDrone.as_dict()`](pymatgen.apps.borg.md#pymatgen.apps.borg.hive.GaussianToComputedEntryDrone.as_dict)


                    * [`GaussianToComputedEntryDrone.assimilate()`](pymatgen.apps.borg.md#pymatgen.apps.borg.hive.GaussianToComputedEntryDrone.assimilate)


                    * [`GaussianToComputedEntryDrone.from_dict()`](pymatgen.apps.borg.md#pymatgen.apps.borg.hive.GaussianToComputedEntryDrone.from_dict)


                    * [`GaussianToComputedEntryDrone.get_valid_paths()`](pymatgen.apps.borg.md#pymatgen.apps.borg.hive.GaussianToComputedEntryDrone.get_valid_paths)


                * [`SimpleVaspToComputedEntryDrone`](pymatgen.apps.borg.md#pymatgen.apps.borg.hive.SimpleVaspToComputedEntryDrone)


                    * [`SimpleVaspToComputedEntryDrone._abc_impl`](pymatgen.apps.borg.md#pymatgen.apps.borg.hive.SimpleVaspToComputedEntryDrone._abc_impl)


                    * [`SimpleVaspToComputedEntryDrone.as_dict()`](pymatgen.apps.borg.md#pymatgen.apps.borg.hive.SimpleVaspToComputedEntryDrone.as_dict)


                    * [`SimpleVaspToComputedEntryDrone.assimilate()`](pymatgen.apps.borg.md#pymatgen.apps.borg.hive.SimpleVaspToComputedEntryDrone.assimilate)


                    * [`SimpleVaspToComputedEntryDrone.from_dict()`](pymatgen.apps.borg.md#pymatgen.apps.borg.hive.SimpleVaspToComputedEntryDrone.from_dict)


                * [`VaspToComputedEntryDrone`](pymatgen.apps.borg.md#pymatgen.apps.borg.hive.VaspToComputedEntryDrone)


                    * [`VaspToComputedEntryDrone._abc_impl`](pymatgen.apps.borg.md#pymatgen.apps.borg.hive.VaspToComputedEntryDrone._abc_impl)


                    * [`VaspToComputedEntryDrone.as_dict()`](pymatgen.apps.borg.md#pymatgen.apps.borg.hive.VaspToComputedEntryDrone.as_dict)


                    * [`VaspToComputedEntryDrone.assimilate()`](pymatgen.apps.borg.md#pymatgen.apps.borg.hive.VaspToComputedEntryDrone.assimilate)


                    * [`VaspToComputedEntryDrone.from_dict()`](pymatgen.apps.borg.md#pymatgen.apps.borg.hive.VaspToComputedEntryDrone.from_dict)


                    * [`VaspToComputedEntryDrone.get_valid_paths()`](pymatgen.apps.borg.md#pymatgen.apps.borg.hive.VaspToComputedEntryDrone.get_valid_paths)


                * [`_get_transformation_history()`](pymatgen.apps.borg.md#pymatgen.apps.borg.hive._get_transformation_history)


            * [pymatgen.apps.borg.queen module](pymatgen.apps.borg.md#module-pymatgen.apps.borg.queen)


                * [`BorgQueen`](pymatgen.apps.borg.md#pymatgen.apps.borg.queen.BorgQueen)


                    * [`BorgQueen.get_data()`](pymatgen.apps.borg.md#pymatgen.apps.borg.queen.BorgQueen.get_data)


                    * [`BorgQueen.load_data()`](pymatgen.apps.borg.md#pymatgen.apps.borg.queen.BorgQueen.load_data)


                    * [`BorgQueen.parallel_assimilate()`](pymatgen.apps.borg.md#pymatgen.apps.borg.queen.BorgQueen.parallel_assimilate)


                    * [`BorgQueen.save_data()`](pymatgen.apps.borg.md#pymatgen.apps.borg.queen.BorgQueen.save_data)


                    * [`BorgQueen.serial_assimilate()`](pymatgen.apps.borg.md#pymatgen.apps.borg.queen.BorgQueen.serial_assimilate)


                * [`order_assimilation()`](pymatgen.apps.borg.md#pymatgen.apps.borg.queen.order_assimilation)


* [pymatgen.cli package](pymatgen.cli.md)




    * [pymatgen.cli.feff_plot_cross_section module](pymatgen.cli.md#module-pymatgen.cli.feff_plot_cross_section)


        * [`main()`](pymatgen.cli.md#pymatgen.cli.feff_plot_cross_section.main)


    * [pymatgen.cli.feff_plot_dos module](pymatgen.cli.md#module-pymatgen.cli.feff_plot_dos)


        * [`main()`](pymatgen.cli.md#pymatgen.cli.feff_plot_dos.main)


    * [pymatgen.cli.get_environment module](pymatgen.cli.md#module-pymatgen.cli.get_environment)


        * [`main()`](pymatgen.cli.md#pymatgen.cli.get_environment.main)


    * [pymatgen.cli.pmg module](pymatgen.cli.md#module-pymatgen.cli.pmg)


        * [`diff_incar()`](pymatgen.cli.md#pymatgen.cli.pmg.diff_incar)


        * [`main()`](pymatgen.cli.md#pymatgen.cli.pmg.main)


        * [`parse_view()`](pymatgen.cli.md#pymatgen.cli.pmg.parse_view)


    * [pymatgen.cli.pmg_analyze module](pymatgen.cli.md#module-pymatgen.cli.pmg_analyze)


        * [`analyze()`](pymatgen.cli.md#pymatgen.cli.pmg_analyze.analyze)


        * [`get_energies()`](pymatgen.cli.md#pymatgen.cli.pmg_analyze.get_energies)


        * [`get_magnetizations()`](pymatgen.cli.md#pymatgen.cli.pmg_analyze.get_magnetizations)


    * [pymatgen.cli.pmg_config module](pymatgen.cli.md#module-pymatgen.cli.pmg_config)


        * [`add_config_var()`](pymatgen.cli.md#pymatgen.cli.pmg_config.add_config_var)


        * [`build_bader()`](pymatgen.cli.md#pymatgen.cli.pmg_config.build_bader)


        * [`build_enum()`](pymatgen.cli.md#pymatgen.cli.pmg_config.build_enum)


        * [`configure_pmg()`](pymatgen.cli.md#pymatgen.cli.pmg_config.configure_pmg)


        * [`install_software()`](pymatgen.cli.md#pymatgen.cli.pmg_config.install_software)


        * [`setup_cp2k_data()`](pymatgen.cli.md#pymatgen.cli.pmg_config.setup_cp2k_data)


        * [`setup_potcars()`](pymatgen.cli.md#pymatgen.cli.pmg_config.setup_potcars)


    * [pymatgen.cli.pmg_plot module](pymatgen.cli.md#module-pymatgen.cli.pmg_plot)


        * [`get_chgint_plot()`](pymatgen.cli.md#pymatgen.cli.pmg_plot.get_chgint_plot)


        * [`get_dos_plot()`](pymatgen.cli.md#pymatgen.cli.pmg_plot.get_dos_plot)


        * [`get_xrd_plot()`](pymatgen.cli.md#pymatgen.cli.pmg_plot.get_xrd_plot)


        * [`plot()`](pymatgen.cli.md#pymatgen.cli.pmg_plot.plot)


    * [pymatgen.cli.pmg_potcar module](pymatgen.cli.md#module-pymatgen.cli.pmg_potcar)


        * [`gen_potcar()`](pymatgen.cli.md#pymatgen.cli.pmg_potcar.gen_potcar)


        * [`generate_potcar()`](pymatgen.cli.md#pymatgen.cli.pmg_potcar.generate_potcar)


        * [`proc_dir()`](pymatgen.cli.md#pymatgen.cli.pmg_potcar.proc_dir)


    * [pymatgen.cli.pmg_query module](pymatgen.cli.md#module-pymatgen.cli.pmg_query)


        * [`do_query()`](pymatgen.cli.md#pymatgen.cli.pmg_query.do_query)


    * [pymatgen.cli.pmg_structure module](pymatgen.cli.md#module-pymatgen.cli.pmg_structure)


        * [`analyze_localenv()`](pymatgen.cli.md#pymatgen.cli.pmg_structure.analyze_localenv)


        * [`analyze_structures()`](pymatgen.cli.md#pymatgen.cli.pmg_structure.analyze_structures)


        * [`analyze_symmetry()`](pymatgen.cli.md#pymatgen.cli.pmg_structure.analyze_symmetry)


        * [`compare_structures()`](pymatgen.cli.md#pymatgen.cli.pmg_structure.compare_structures)


        * [`convert_fmt()`](pymatgen.cli.md#pymatgen.cli.pmg_structure.convert_fmt)


* [pymatgen.command_line package](pymatgen.command_line.md)




    * [pymatgen.command_line.bader_caller module](pymatgen.command_line.md#module-pymatgen.command_line.bader_caller)


        * [`BaderAnalysis`](pymatgen.command_line.md#pymatgen.command_line.bader_caller.BaderAnalysis)


            * [`BaderAnalysis.data`](pymatgen.command_line.md#pymatgen.command_line.bader_caller.BaderAnalysis.data)


            * [`BaderAnalysis.vacuum_volume`](pymatgen.command_line.md#pymatgen.command_line.bader_caller.BaderAnalysis.vacuum_volume)


            * [`BaderAnalysis.vacuum_charge`](pymatgen.command_line.md#pymatgen.command_line.bader_caller.BaderAnalysis.vacuum_charge)


            * [`BaderAnalysis.nelectrons`](pymatgen.command_line.md#pymatgen.command_line.bader_caller.BaderAnalysis.nelectrons)


            * [`BaderAnalysis.chgcar`](pymatgen.command_line.md#pymatgen.command_line.bader_caller.BaderAnalysis.chgcar)


            * [`BaderAnalysis.atomic_densities`](pymatgen.command_line.md#pymatgen.command_line.bader_caller.BaderAnalysis.atomic_densities)


            * [`BaderAnalysis.from_path()`](pymatgen.command_line.md#pymatgen.command_line.bader_caller.BaderAnalysis.from_path)


            * [`BaderAnalysis.get_charge()`](pymatgen.command_line.md#pymatgen.command_line.bader_caller.BaderAnalysis.get_charge)


            * [`BaderAnalysis.get_charge_decorated_structure()`](pymatgen.command_line.md#pymatgen.command_line.bader_caller.BaderAnalysis.get_charge_decorated_structure)


            * [`BaderAnalysis.get_charge_transfer()`](pymatgen.command_line.md#pymatgen.command_line.bader_caller.BaderAnalysis.get_charge_transfer)


            * [`BaderAnalysis.get_decorated_structure()`](pymatgen.command_line.md#pymatgen.command_line.bader_caller.BaderAnalysis.get_decorated_structure)


            * [`BaderAnalysis.get_oxidation_state_decorated_structure()`](pymatgen.command_line.md#pymatgen.command_line.bader_caller.BaderAnalysis.get_oxidation_state_decorated_structure)


            * [`BaderAnalysis.get_partial_charge()`](pymatgen.command_line.md#pymatgen.command_line.bader_caller.BaderAnalysis.get_partial_charge)


            * [`BaderAnalysis.summary`](pymatgen.command_line.md#pymatgen.command_line.bader_caller.BaderAnalysis.summary)


        * [`bader_analysis_from_objects()`](pymatgen.command_line.md#pymatgen.command_line.bader_caller.bader_analysis_from_objects)


        * [`bader_analysis_from_path()`](pymatgen.command_line.md#pymatgen.command_line.bader_caller.bader_analysis_from_path)


    * [pymatgen.command_line.chargemol_caller module](pymatgen.command_line.md#module-pymatgen.command_line.chargemol_caller)


        * [`ChargemolAnalysis`](pymatgen.command_line.md#pymatgen.command_line.chargemol_caller.ChargemolAnalysis)


            * [`ChargemolAnalysis._execute_chargemol()`](pymatgen.command_line.md#pymatgen.command_line.chargemol_caller.ChargemolAnalysis._execute_chargemol)


            * [`ChargemolAnalysis._from_data_dir()`](pymatgen.command_line.md#pymatgen.command_line.chargemol_caller.ChargemolAnalysis._from_data_dir)


            * [`ChargemolAnalysis._get_bond_order_info()`](pymatgen.command_line.md#pymatgen.command_line.chargemol_caller.ChargemolAnalysis._get_bond_order_info)


            * [`ChargemolAnalysis._get_cm5_data_from_output()`](pymatgen.command_line.md#pymatgen.command_line.chargemol_caller.ChargemolAnalysis._get_cm5_data_from_output)


            * [`ChargemolAnalysis._get_data_from_xyz()`](pymatgen.command_line.md#pymatgen.command_line.chargemol_caller.ChargemolAnalysis._get_data_from_xyz)


            * [`ChargemolAnalysis._get_dipole_info()`](pymatgen.command_line.md#pymatgen.command_line.chargemol_caller.ChargemolAnalysis._get_dipole_info)


            * [`ChargemolAnalysis._get_filepath()`](pymatgen.command_line.md#pymatgen.command_line.chargemol_caller.ChargemolAnalysis._get_filepath)


            * [`ChargemolAnalysis._write_jobscript_for_chargemol()`](pymatgen.command_line.md#pymatgen.command_line.chargemol_caller.ChargemolAnalysis._write_jobscript_for_chargemol)


            * [`ChargemolAnalysis.get_bond_order()`](pymatgen.command_line.md#pymatgen.command_line.chargemol_caller.ChargemolAnalysis.get_bond_order)


            * [`ChargemolAnalysis.get_charge()`](pymatgen.command_line.md#pymatgen.command_line.chargemol_caller.ChargemolAnalysis.get_charge)


            * [`ChargemolAnalysis.get_charge_transfer()`](pymatgen.command_line.md#pymatgen.command_line.chargemol_caller.ChargemolAnalysis.get_charge_transfer)


            * [`ChargemolAnalysis.get_partial_charge()`](pymatgen.command_line.md#pymatgen.command_line.chargemol_caller.ChargemolAnalysis.get_partial_charge)


            * [`ChargemolAnalysis.get_property_decorated_structure()`](pymatgen.command_line.md#pymatgen.command_line.chargemol_caller.ChargemolAnalysis.get_property_decorated_structure)


            * [`ChargemolAnalysis.summary`](pymatgen.command_line.md#pymatgen.command_line.chargemol_caller.ChargemolAnalysis.summary)


    * [pymatgen.command_line.critic2_caller module](pymatgen.command_line.md#module-pymatgen.command_line.critic2_caller)


        * [`Critic2Analysis`](pymatgen.command_line.md#pymatgen.command_line.critic2_caller.Critic2Analysis)


            * [`Critic2Analysis._add_edge()`](pymatgen.command_line.md#pymatgen.command_line.critic2_caller.Critic2Analysis._add_edge)


            * [`Critic2Analysis._add_node()`](pymatgen.command_line.md#pymatgen.command_line.critic2_caller.Critic2Analysis._add_node)


            * [`Critic2Analysis._annotate_structure_with_yt()`](pymatgen.command_line.md#pymatgen.command_line.critic2_caller.Critic2Analysis._annotate_structure_with_yt)


            * [`Critic2Analysis._parse_cpreport()`](pymatgen.command_line.md#pymatgen.command_line.critic2_caller.Critic2Analysis._parse_cpreport)


            * [`Critic2Analysis._parse_stdout()`](pymatgen.command_line.md#pymatgen.command_line.critic2_caller.Critic2Analysis._parse_stdout)


            * [`Critic2Analysis._remap_indices()`](pymatgen.command_line.md#pymatgen.command_line.critic2_caller.Critic2Analysis._remap_indices)


            * [`Critic2Analysis.get_critical_point_for_site()`](pymatgen.command_line.md#pymatgen.command_line.critic2_caller.Critic2Analysis.get_critical_point_for_site)


            * [`Critic2Analysis.get_volume_and_charge_for_site()`](pymatgen.command_line.md#pymatgen.command_line.critic2_caller.Critic2Analysis.get_volume_and_charge_for_site)


            * [`Critic2Analysis.structure_graph()`](pymatgen.command_line.md#pymatgen.command_line.critic2_caller.Critic2Analysis.structure_graph)


        * [`Critic2Caller`](pymatgen.command_line.md#pymatgen.command_line.critic2_caller.Critic2Caller)


            * [`Critic2Caller.from_chgcar()`](pymatgen.command_line.md#pymatgen.command_line.critic2_caller.Critic2Caller.from_chgcar)


            * [`Critic2Caller.from_path()`](pymatgen.command_line.md#pymatgen.command_line.critic2_caller.Critic2Caller.from_path)


        * [`CriticalPoint`](pymatgen.command_line.md#pymatgen.command_line.critic2_caller.CriticalPoint)


            * [`CriticalPoint.ellipticity`](pymatgen.command_line.md#pymatgen.command_line.critic2_caller.CriticalPoint.ellipticity)


            * [`CriticalPoint.laplacian`](pymatgen.command_line.md#pymatgen.command_line.critic2_caller.CriticalPoint.laplacian)


            * [`CriticalPoint.type`](pymatgen.command_line.md#pymatgen.command_line.critic2_caller.CriticalPoint.type)


        * [`CriticalPointType`](pymatgen.command_line.md#pymatgen.command_line.critic2_caller.CriticalPointType)


            * [`CriticalPointType.bond`](pymatgen.command_line.md#pymatgen.command_line.critic2_caller.CriticalPointType.bond)


            * [`CriticalPointType.cage`](pymatgen.command_line.md#pymatgen.command_line.critic2_caller.CriticalPointType.cage)


            * [`CriticalPointType.nnattr`](pymatgen.command_line.md#pymatgen.command_line.critic2_caller.CriticalPointType.nnattr)


            * [`CriticalPointType.nucleus`](pymatgen.command_line.md#pymatgen.command_line.critic2_caller.CriticalPointType.nucleus)


            * [`CriticalPointType.ring`](pymatgen.command_line.md#pymatgen.command_line.critic2_caller.CriticalPointType.ring)


        * [`get_filepath()`](pymatgen.command_line.md#pymatgen.command_line.critic2_caller.get_filepath)


    * [pymatgen.command_line.enumlib_caller module](pymatgen.command_line.md#module-pymatgen.command_line.enumlib_caller)


        * [`EnumError`](pymatgen.command_line.md#pymatgen.command_line.enumlib_caller.EnumError)


        * [`EnumlibAdaptor()`](pymatgen.command_line.md#pymatgen.command_line.enumlib_caller.EnumlibAdaptor)


        * [`structures`](pymatgen.command_line.md#pymatgen.command_line.enumlib_caller.structures)


    * [pymatgen.command_line.gulp_caller module](pymatgen.command_line.md#module-pymatgen.command_line.gulp_caller)


        * [`BuckinghamPotential`](pymatgen.command_line.md#pymatgen.command_line.gulp_caller.BuckinghamPotential)


        * [`GulpCaller`](pymatgen.command_line.md#pymatgen.command_line.gulp_caller.GulpCaller)


            * [`GulpCaller.run()`](pymatgen.command_line.md#pymatgen.command_line.gulp_caller.GulpCaller.run)


        * [`GulpConvergenceError`](pymatgen.command_line.md#pymatgen.command_line.gulp_caller.GulpConvergenceError)


        * [`GulpError`](pymatgen.command_line.md#pymatgen.command_line.gulp_caller.GulpError)


        * [`GulpIO`](pymatgen.command_line.md#pymatgen.command_line.gulp_caller.GulpIO)


            * [`GulpIO.buckingham_input()`](pymatgen.command_line.md#pymatgen.command_line.gulp_caller.GulpIO.buckingham_input)


            * [`GulpIO.buckingham_potential()`](pymatgen.command_line.md#pymatgen.command_line.gulp_caller.GulpIO.buckingham_potential)


            * [`GulpIO.get_energy()`](pymatgen.command_line.md#pymatgen.command_line.gulp_caller.GulpIO.get_energy)


            * [`GulpIO.get_relaxed_structure()`](pymatgen.command_line.md#pymatgen.command_line.gulp_caller.GulpIO.get_relaxed_structure)


            * [`GulpIO.keyword_line()`](pymatgen.command_line.md#pymatgen.command_line.gulp_caller.GulpIO.keyword_line)


            * [`GulpIO.library_line()`](pymatgen.command_line.md#pymatgen.command_line.gulp_caller.GulpIO.library_line)


            * [`GulpIO.specie_potential_lines()`](pymatgen.command_line.md#pymatgen.command_line.gulp_caller.GulpIO.specie_potential_lines)


            * [`GulpIO.structure_lines()`](pymatgen.command_line.md#pymatgen.command_line.gulp_caller.GulpIO.structure_lines)


            * [`GulpIO.tersoff_input()`](pymatgen.command_line.md#pymatgen.command_line.gulp_caller.GulpIO.tersoff_input)


            * [`GulpIO.tersoff_potential()`](pymatgen.command_line.md#pymatgen.command_line.gulp_caller.GulpIO.tersoff_potential)


        * [`TersoffPotential`](pymatgen.command_line.md#pymatgen.command_line.gulp_caller.TersoffPotential)


        * [`get_energy_buckingham()`](pymatgen.command_line.md#pymatgen.command_line.gulp_caller.get_energy_buckingham)


        * [`get_energy_relax_structure_buckingham()`](pymatgen.command_line.md#pymatgen.command_line.gulp_caller.get_energy_relax_structure_buckingham)


        * [`get_energy_tersoff()`](pymatgen.command_line.md#pymatgen.command_line.gulp_caller.get_energy_tersoff)


    * [pymatgen.command_line.mcsqs_caller module](pymatgen.command_line.md#module-pymatgen.command_line.mcsqs_caller)


        * [`Sqs`](pymatgen.command_line.md#pymatgen.command_line.mcsqs_caller.Sqs)


            * [`Sqs._asdict()`](pymatgen.command_line.md#pymatgen.command_line.mcsqs_caller.Sqs._asdict)


            * [`Sqs._field_defaults`](pymatgen.command_line.md#pymatgen.command_line.mcsqs_caller.Sqs._field_defaults)


            * [`Sqs._fields`](pymatgen.command_line.md#pymatgen.command_line.mcsqs_caller.Sqs._fields)


            * [`Sqs._make()`](pymatgen.command_line.md#pymatgen.command_line.mcsqs_caller.Sqs._make)


            * [`Sqs._replace()`](pymatgen.command_line.md#pymatgen.command_line.mcsqs_caller.Sqs._replace)


            * [`Sqs.allsqs`](pymatgen.command_line.md#pymatgen.command_line.mcsqs_caller.Sqs.allsqs)


            * [`Sqs.bestsqs`](pymatgen.command_line.md#pymatgen.command_line.mcsqs_caller.Sqs.bestsqs)


            * [`Sqs.clusters`](pymatgen.command_line.md#pymatgen.command_line.mcsqs_caller.Sqs.clusters)


            * [`Sqs.directory`](pymatgen.command_line.md#pymatgen.command_line.mcsqs_caller.Sqs.directory)


            * [`Sqs.objective_function`](pymatgen.command_line.md#pymatgen.command_line.mcsqs_caller.Sqs.objective_function)


        * [`_parse_clusters()`](pymatgen.command_line.md#pymatgen.command_line.mcsqs_caller._parse_clusters)


        * [`_parse_sqs_path()`](pymatgen.command_line.md#pymatgen.command_line.mcsqs_caller._parse_sqs_path)


        * [`run_mcsqs()`](pymatgen.command_line.md#pymatgen.command_line.mcsqs_caller.run_mcsqs)


    * [pymatgen.command_line.vampire_caller module](pymatgen.command_line.md#module-pymatgen.command_line.vampire_caller)


        * [`VampireCaller`](pymatgen.command_line.md#pymatgen.command_line.vampire_caller.VampireCaller)


            * [`VampireCaller._create_input()`](pymatgen.command_line.md#pymatgen.command_line.vampire_caller.VampireCaller._create_input)


            * [`VampireCaller._create_mat()`](pymatgen.command_line.md#pymatgen.command_line.vampire_caller.VampireCaller._create_mat)


            * [`VampireCaller._create_ucf()`](pymatgen.command_line.md#pymatgen.command_line.vampire_caller.VampireCaller._create_ucf)


            * [`VampireCaller.parse_stdout()`](pymatgen.command_line.md#pymatgen.command_line.vampire_caller.VampireCaller.parse_stdout)


        * [`VampireOutput`](pymatgen.command_line.md#pymatgen.command_line.vampire_caller.VampireOutput)


* [pymatgen.core package](pymatgen.core.md)


    * [`_load_pmg_settings()`](pymatgen.core.md#pymatgen.core._load_pmg_settings)




    * [pymatgen.core.bonds module](pymatgen.core.md#module-pymatgen.core.bonds)


        * [`CovalentBond`](pymatgen.core.md#pymatgen.core.bonds.CovalentBond)


            * [`CovalentBond.get_bond_order()`](pymatgen.core.md#pymatgen.core.bonds.CovalentBond.get_bond_order)


            * [`CovalentBond.is_bonded()`](pymatgen.core.md#pymatgen.core.bonds.CovalentBond.is_bonded)


            * [`CovalentBond.length`](pymatgen.core.md#pymatgen.core.bonds.CovalentBond.length)


        * [`_load_bond_length_data()`](pymatgen.core.md#pymatgen.core.bonds._load_bond_length_data)


        * [`get_bond_length()`](pymatgen.core.md#pymatgen.core.bonds.get_bond_length)


        * [`get_bond_order()`](pymatgen.core.md#pymatgen.core.bonds.get_bond_order)


        * [`obtain_all_bond_lengths()`](pymatgen.core.md#pymatgen.core.bonds.obtain_all_bond_lengths)


    * [pymatgen.core.composition module](pymatgen.core.md#module-pymatgen.core.composition)


        * [`ChemicalPotential`](pymatgen.core.md#pymatgen.core.composition.ChemicalPotential)


            * [`ChemicalPotential.get_energy()`](pymatgen.core.md#pymatgen.core.composition.ChemicalPotential.get_energy)


        * [`Composition`](pymatgen.core.md#pymatgen.core.composition.Composition)


            * [`Composition._abc_impl`](pymatgen.core.md#pymatgen.core.composition.Composition._abc_impl)


            * [`Composition._comps_from_fuzzy_formula()`](pymatgen.core.md#pymatgen.core.composition.Composition._comps_from_fuzzy_formula)


            * [`Composition._get_oxi_state_guesses()`](pymatgen.core.md#pymatgen.core.composition.Composition._get_oxi_state_guesses)


            * [`Composition._parse_formula()`](pymatgen.core.md#pymatgen.core.composition.Composition._parse_formula)


            * [`Composition.add_charges_from_oxi_state_guesses()`](pymatgen.core.md#pymatgen.core.composition.Composition.add_charges_from_oxi_state_guesses)


            * [`Composition.almost_equals()`](pymatgen.core.md#pymatgen.core.composition.Composition.almost_equals)


            * [`Composition.alphabetical_formula`](pymatgen.core.md#pymatgen.core.composition.Composition.alphabetical_formula)


            * [`Composition.amount_tolerance`](pymatgen.core.md#pymatgen.core.composition.Composition.amount_tolerance)


            * [`Composition.anonymized_formula`](pymatgen.core.md#pymatgen.core.composition.Composition.anonymized_formula)


            * [`Composition.as_dict()`](pymatgen.core.md#pymatgen.core.composition.Composition.as_dict)


            * [`Composition.average_electroneg`](pymatgen.core.md#pymatgen.core.composition.Composition.average_electroneg)


            * [`Composition.chemical_system`](pymatgen.core.md#pymatgen.core.composition.Composition.chemical_system)


            * [`Composition.contains_element_type()`](pymatgen.core.md#pymatgen.core.composition.Composition.contains_element_type)


            * [`Composition.copy()`](pymatgen.core.md#pymatgen.core.composition.Composition.copy)


            * [`Composition.element_composition`](pymatgen.core.md#pymatgen.core.composition.Composition.element_composition)


            * [`Composition.elements`](pymatgen.core.md#pymatgen.core.composition.Composition.elements)


            * [`Composition.formula`](pymatgen.core.md#pymatgen.core.composition.Composition.formula)


            * [`Composition.fractional_composition`](pymatgen.core.md#pymatgen.core.composition.Composition.fractional_composition)


            * [`Composition.from_dict()`](pymatgen.core.md#pymatgen.core.composition.Composition.from_dict)


            * [`Composition.from_weight_dict()`](pymatgen.core.md#pymatgen.core.composition.Composition.from_weight_dict)


            * [`Composition.get_atomic_fraction()`](pymatgen.core.md#pymatgen.core.composition.Composition.get_atomic_fraction)


            * [`Composition.get_el_amt_dict()`](pymatgen.core.md#pymatgen.core.composition.Composition.get_el_amt_dict)


            * [`Composition.get_integer_formula_and_factor()`](pymatgen.core.md#pymatgen.core.composition.Composition.get_integer_formula_and_factor)


            * [`Composition.get_reduced_composition_and_factor()`](pymatgen.core.md#pymatgen.core.composition.Composition.get_reduced_composition_and_factor)


            * [`Composition.get_reduced_formula_and_factor()`](pymatgen.core.md#pymatgen.core.composition.Composition.get_reduced_formula_and_factor)


            * [`Composition.get_wt_fraction()`](pymatgen.core.md#pymatgen.core.composition.Composition.get_wt_fraction)


            * [`Composition.hill_formula`](pymatgen.core.md#pymatgen.core.composition.Composition.hill_formula)


            * [`Composition.is_element`](pymatgen.core.md#pymatgen.core.composition.Composition.is_element)


            * [`Composition.iupac_formula`](pymatgen.core.md#pymatgen.core.composition.Composition.iupac_formula)


            * [`Composition.num_atoms`](pymatgen.core.md#pymatgen.core.composition.Composition.num_atoms)


            * [`Composition.oxi_prob`](pymatgen.core.md#pymatgen.core.composition.Composition.oxi_prob)


            * [`Composition.oxi_state_guesses()`](pymatgen.core.md#pymatgen.core.composition.Composition.oxi_state_guesses)


            * [`Composition.ranked_compositions_from_indeterminate_formula()`](pymatgen.core.md#pymatgen.core.composition.Composition.ranked_compositions_from_indeterminate_formula)


            * [`Composition.reduced_composition`](pymatgen.core.md#pymatgen.core.composition.Composition.reduced_composition)


            * [`Composition.reduced_formula`](pymatgen.core.md#pymatgen.core.composition.Composition.reduced_formula)


            * [`Composition.remove_charges()`](pymatgen.core.md#pymatgen.core.composition.Composition.remove_charges)


            * [`Composition.replace()`](pymatgen.core.md#pymatgen.core.composition.Composition.replace)


            * [`Composition.special_formulas`](pymatgen.core.md#pymatgen.core.composition.Composition.special_formulas)


            * [`Composition.to_data_dict`](pymatgen.core.md#pymatgen.core.composition.Composition.to_data_dict)


            * [`Composition.to_pretty_string()`](pymatgen.core.md#pymatgen.core.composition.Composition.to_pretty_string)


            * [`Composition.to_reduced_dict`](pymatgen.core.md#pymatgen.core.composition.Composition.to_reduced_dict)


            * [`Composition.to_weight_dict`](pymatgen.core.md#pymatgen.core.composition.Composition.to_weight_dict)


            * [`Composition.total_electrons`](pymatgen.core.md#pymatgen.core.composition.Composition.total_electrons)


            * [`Composition.valid`](pymatgen.core.md#pymatgen.core.composition.Composition.valid)


            * [`Composition.weight`](pymatgen.core.md#pymatgen.core.composition.Composition.weight)


        * [`CompositionError`](pymatgen.core.md#pymatgen.core.composition.CompositionError)


        * [`reduce_formula()`](pymatgen.core.md#pymatgen.core.composition.reduce_formula)


    * [pymatgen.core.interface module](pymatgen.core.md#module-pymatgen.core.interface)


        * [`Interface`](pymatgen.core.md#pymatgen.core.interface.Interface)


            * [`Interface._abc_impl`](pymatgen.core.md#pymatgen.core.interface.Interface._abc_impl)


            * [`Interface._properties`](pymatgen.core.md#pymatgen.core.interface.Interface._properties)


            * [`Interface._update_c()`](pymatgen.core.md#pymatgen.core.interface.Interface._update_c)


            * [`Interface.as_dict()`](pymatgen.core.md#pymatgen.core.interface.Interface.as_dict)


            * [`Interface.copy()`](pymatgen.core.md#pymatgen.core.interface.Interface.copy)


            * [`Interface.film`](pymatgen.core.md#pymatgen.core.interface.Interface.film)


            * [`Interface.film_indices`](pymatgen.core.md#pymatgen.core.interface.Interface.film_indices)


            * [`Interface.film_layers`](pymatgen.core.md#pymatgen.core.interface.Interface.film_layers)


            * [`Interface.film_sites`](pymatgen.core.md#pymatgen.core.interface.Interface.film_sites)


            * [`Interface.film_termination`](pymatgen.core.md#pymatgen.core.interface.Interface.film_termination)


            * [`Interface.from_dict()`](pymatgen.core.md#pymatgen.core.interface.Interface.from_dict)


            * [`Interface.from_slabs()`](pymatgen.core.md#pymatgen.core.interface.Interface.from_slabs)


            * [`Interface.gap`](pymatgen.core.md#pymatgen.core.interface.Interface.gap)


            * [`Interface.get_shifts_based_on_adsorbate_sites()`](pymatgen.core.md#pymatgen.core.interface.Interface.get_shifts_based_on_adsorbate_sites)


            * [`Interface.get_sorted_structure()`](pymatgen.core.md#pymatgen.core.interface.Interface.get_sorted_structure)


            * [`Interface.in_plane_offset`](pymatgen.core.md#pymatgen.core.interface.Interface.in_plane_offset)


            * [`Interface.substrate`](pymatgen.core.md#pymatgen.core.interface.Interface.substrate)


            * [`Interface.substrate_indices`](pymatgen.core.md#pymatgen.core.interface.Interface.substrate_indices)


            * [`Interface.substrate_layers`](pymatgen.core.md#pymatgen.core.interface.Interface.substrate_layers)


            * [`Interface.substrate_sites`](pymatgen.core.md#pymatgen.core.interface.Interface.substrate_sites)


            * [`Interface.substrate_termination`](pymatgen.core.md#pymatgen.core.interface.Interface.substrate_termination)


            * [`Interface.vacuum_over_film`](pymatgen.core.md#pymatgen.core.interface.Interface.vacuum_over_film)


        * [`count_layers()`](pymatgen.core.md#pymatgen.core.interface.count_layers)


        * [`label_termination()`](pymatgen.core.md#pymatgen.core.interface.label_termination)


    * [pymatgen.core.ion module](pymatgen.core.md#module-pymatgen.core.ion)


        * [`Ion`](pymatgen.core.md#pymatgen.core.ion.Ion)


            * [`Ion._abc_impl`](pymatgen.core.md#pymatgen.core.ion.Ion._abc_impl)


            * [`Ion.alphabetical_formula`](pymatgen.core.md#pymatgen.core.ion.Ion.alphabetical_formula)


            * [`Ion.anonymized_formula`](pymatgen.core.md#pymatgen.core.ion.Ion.anonymized_formula)


            * [`Ion.as_dict()`](pymatgen.core.md#pymatgen.core.ion.Ion.as_dict)


            * [`Ion.charge`](pymatgen.core.md#pymatgen.core.ion.Ion.charge)


            * [`Ion.composition`](pymatgen.core.md#pymatgen.core.ion.Ion.composition)


            * [`Ion.formula`](pymatgen.core.md#pymatgen.core.ion.Ion.formula)


            * [`Ion.from_dict()`](pymatgen.core.md#pymatgen.core.ion.Ion.from_dict)


            * [`Ion.from_formula()`](pymatgen.core.md#pymatgen.core.ion.Ion.from_formula)


            * [`Ion.get_reduced_formula_and_factor()`](pymatgen.core.md#pymatgen.core.ion.Ion.get_reduced_formula_and_factor)


            * [`Ion.oxi_state_guesses()`](pymatgen.core.md#pymatgen.core.ion.Ion.oxi_state_guesses)


            * [`Ion.reduced_formula`](pymatgen.core.md#pymatgen.core.ion.Ion.reduced_formula)


            * [`Ion.to_pretty_string()`](pymatgen.core.md#pymatgen.core.ion.Ion.to_pretty_string)


            * [`Ion.to_reduced_dict`](pymatgen.core.md#pymatgen.core.ion.Ion.to_reduced_dict)


    * [pymatgen.core.lattice module](pymatgen.core.md#module-pymatgen.core.lattice)


        * [`Lattice`](pymatgen.core.md#pymatgen.core.lattice.Lattice)


            * [`Lattice._calculate_lll()`](pymatgen.core.md#pymatgen.core.lattice.Lattice._calculate_lll)


            * [`Lattice.a`](pymatgen.core.md#pymatgen.core.lattice.Lattice.a)


            * [`Lattice.abc`](pymatgen.core.md#pymatgen.core.lattice.Lattice.abc)


            * [`Lattice.alpha`](pymatgen.core.md#pymatgen.core.lattice.Lattice.alpha)


            * [`Lattice.angles`](pymatgen.core.md#pymatgen.core.lattice.Lattice.angles)


            * [`Lattice.as_dict()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.as_dict)


            * [`Lattice.b`](pymatgen.core.md#pymatgen.core.lattice.Lattice.b)


            * [`Lattice.beta`](pymatgen.core.md#pymatgen.core.lattice.Lattice.beta)


            * [`Lattice.c`](pymatgen.core.md#pymatgen.core.lattice.Lattice.c)


            * [`Lattice.copy()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.copy)


            * [`Lattice.cubic()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.cubic)


            * [`Lattice.d_hkl()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.d_hkl)


            * [`Lattice.dot()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.dot)


            * [`Lattice.find_all_mappings()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.find_all_mappings)


            * [`Lattice.find_mapping()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.find_mapping)


            * [`Lattice.from_dict()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.from_dict)


            * [`Lattice.from_parameters()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.from_parameters)


            * [`Lattice.gamma`](pymatgen.core.md#pymatgen.core.lattice.Lattice.gamma)


            * [`Lattice.get_all_distances()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.get_all_distances)


            * [`Lattice.get_brillouin_zone()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.get_brillouin_zone)


            * [`Lattice.get_cartesian_coords()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.get_cartesian_coords)


            * [`Lattice.get_distance_and_image()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.get_distance_and_image)


            * [`Lattice.get_frac_coords_from_lll()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.get_frac_coords_from_lll)


            * [`Lattice.get_fractional_coords()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.get_fractional_coords)


            * [`Lattice.get_lll_frac_coords()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.get_lll_frac_coords)


            * [`Lattice.get_lll_reduced_lattice()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.get_lll_reduced_lattice)


            * [`Lattice.get_miller_index_from_coords()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.get_miller_index_from_coords)


            * [`Lattice.get_niggli_reduced_lattice()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.get_niggli_reduced_lattice)


            * [`Lattice.get_points_in_sphere()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.get_points_in_sphere)


            * [`Lattice.get_points_in_sphere_old()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.get_points_in_sphere_old)


            * [`Lattice.get_points_in_sphere_py()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.get_points_in_sphere_py)


            * [`Lattice.get_recp_symmetry_operation()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.get_recp_symmetry_operation)


            * [`Lattice.get_vector_along_lattice_directions()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.get_vector_along_lattice_directions)


            * [`Lattice.get_wigner_seitz_cell()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.get_wigner_seitz_cell)


            * [`Lattice.hexagonal()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.hexagonal)


            * [`Lattice.inv_matrix`](pymatgen.core.md#pymatgen.core.lattice.Lattice.inv_matrix)


            * [`Lattice.is_3d_periodic`](pymatgen.core.md#pymatgen.core.lattice.Lattice.is_3d_periodic)


            * [`Lattice.is_hexagonal()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.is_hexagonal)


            * [`Lattice.is_orthogonal`](pymatgen.core.md#pymatgen.core.lattice.Lattice.is_orthogonal)


            * [`Lattice.lengths`](pymatgen.core.md#pymatgen.core.lattice.Lattice.lengths)


            * [`Lattice.lll_inverse`](pymatgen.core.md#pymatgen.core.lattice.Lattice.lll_inverse)


            * [`Lattice.lll_mapping`](pymatgen.core.md#pymatgen.core.lattice.Lattice.lll_mapping)


            * [`Lattice.lll_matrix`](pymatgen.core.md#pymatgen.core.lattice.Lattice.lll_matrix)


            * [`Lattice.matrix`](pymatgen.core.md#pymatgen.core.lattice.Lattice.matrix)


            * [`Lattice.metric_tensor`](pymatgen.core.md#pymatgen.core.lattice.Lattice.metric_tensor)


            * [`Lattice.monoclinic()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.monoclinic)


            * [`Lattice.norm()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.norm)


            * [`Lattice.orthorhombic()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.orthorhombic)


            * [`Lattice.parameters`](pymatgen.core.md#pymatgen.core.lattice.Lattice.parameters)


            * [`Lattice.params_dict`](pymatgen.core.md#pymatgen.core.lattice.Lattice.params_dict)


            * [`Lattice.pbc`](pymatgen.core.md#pymatgen.core.lattice.Lattice.pbc)


            * [`Lattice.reciprocal_lattice`](pymatgen.core.md#pymatgen.core.lattice.Lattice.reciprocal_lattice)


            * [`Lattice.reciprocal_lattice_crystallographic`](pymatgen.core.md#pymatgen.core.lattice.Lattice.reciprocal_lattice_crystallographic)


            * [`Lattice.rhombohedral()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.rhombohedral)


            * [`Lattice.scale()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.scale)


            * [`Lattice.selling_dist()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.selling_dist)


            * [`Lattice.selling_vector`](pymatgen.core.md#pymatgen.core.lattice.Lattice.selling_vector)


            * [`Lattice.tetragonal()`](pymatgen.core.md#pymatgen.core.lattice.Lattice.tetragonal)


            * [`Lattice.volume`](pymatgen.core.md#pymatgen.core.lattice.Lattice.volume)


        * [`_compute_cube_index()`](pymatgen.core.md#pymatgen.core.lattice._compute_cube_index)


        * [`_one_to_three()`](pymatgen.core.md#pymatgen.core.lattice._one_to_three)


        * [`_three_to_one()`](pymatgen.core.md#pymatgen.core.lattice._three_to_one)


        * [`find_neighbors()`](pymatgen.core.md#pymatgen.core.lattice.find_neighbors)


        * [`get_integer_index()`](pymatgen.core.md#pymatgen.core.lattice.get_integer_index)


        * [`get_points_in_spheres()`](pymatgen.core.md#pymatgen.core.lattice.get_points_in_spheres)


    * [pymatgen.core.libxcfunc module](pymatgen.core.md#module-pymatgen.core.libxcfunc)


        * [`LibxcFunc`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc)


            * [`LibxcFunc.GGA_C_AM05`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_AM05)


            * [`LibxcFunc.GGA_C_APBE`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_APBE)


            * [`LibxcFunc.GGA_C_BGCP`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_BGCP)


            * [`LibxcFunc.GGA_C_FT97`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_FT97)


            * [`LibxcFunc.GGA_C_GAM`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_GAM)


            * [`LibxcFunc.GGA_C_HCTH_A`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_HCTH_A)


            * [`LibxcFunc.GGA_C_LM`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_LM)


            * [`LibxcFunc.GGA_C_LYP`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_LYP)


            * [`LibxcFunc.GGA_C_N12`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_N12)


            * [`LibxcFunc.GGA_C_N12_SX`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_N12_SX)


            * [`LibxcFunc.GGA_C_OPTC`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_OPTC)


            * [`LibxcFunc.GGA_C_OP_B88`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_OP_B88)


            * [`LibxcFunc.GGA_C_OP_G96`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_OP_G96)


            * [`LibxcFunc.GGA_C_OP_PBE`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_OP_PBE)


            * [`LibxcFunc.GGA_C_OP_PW91`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_OP_PW91)


            * [`LibxcFunc.GGA_C_OP_XALPHA`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_OP_XALPHA)


            * [`LibxcFunc.GGA_C_P86`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_P86)


            * [`LibxcFunc.GGA_C_PBE`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_PBE)


            * [`LibxcFunc.GGA_C_PBEFE`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_PBEFE)


            * [`LibxcFunc.GGA_C_PBEINT`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_PBEINT)


            * [`LibxcFunc.GGA_C_PBELOC`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_PBELOC)


            * [`LibxcFunc.GGA_C_PBE_JRGX`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_PBE_JRGX)


            * [`LibxcFunc.GGA_C_PBE_SOL`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_PBE_SOL)


            * [`LibxcFunc.GGA_C_PW91`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_PW91)


            * [`LibxcFunc.GGA_C_Q2D`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_Q2D)


            * [`LibxcFunc.GGA_C_REGTPSS`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_REGTPSS)


            * [`LibxcFunc.GGA_C_REVTCA`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_REVTCA)


            * [`LibxcFunc.GGA_C_RGE2`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_RGE2)


            * [`LibxcFunc.GGA_C_SOGGA11`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_SOGGA11)


            * [`LibxcFunc.GGA_C_SOGGA11_X`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_SOGGA11_X)


            * [`LibxcFunc.GGA_C_SPBE`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_SPBE)


            * [`LibxcFunc.GGA_C_TCA`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_TCA)


            * [`LibxcFunc.GGA_C_WI`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_WI)


            * [`LibxcFunc.GGA_C_WI0`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_WI0)


            * [`LibxcFunc.GGA_C_WL`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_WL)


            * [`LibxcFunc.GGA_C_XPBE`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_XPBE)


            * [`LibxcFunc.GGA_C_ZPBEINT`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_ZPBEINT)


            * [`LibxcFunc.GGA_C_ZPBESOL`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_C_ZPBESOL)


            * [`LibxcFunc.GGA_K_ABSP1`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_ABSP1)


            * [`LibxcFunc.GGA_K_ABSP2`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_ABSP2)


            * [`LibxcFunc.GGA_K_APBE`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_APBE)


            * [`LibxcFunc.GGA_K_APBEINT`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_APBEINT)


            * [`LibxcFunc.GGA_K_BALTIN`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_BALTIN)


            * [`LibxcFunc.GGA_K_DK`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_DK)


            * [`LibxcFunc.GGA_K_ERNZERHOF`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_ERNZERHOF)


            * [`LibxcFunc.GGA_K_FR_B88`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_FR_B88)


            * [`LibxcFunc.GGA_K_FR_PW86`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_FR_PW86)


            * [`LibxcFunc.GGA_K_GE2`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_GE2)


            * [`LibxcFunc.GGA_K_GOLDEN`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_GOLDEN)


            * [`LibxcFunc.GGA_K_GP85`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_GP85)


            * [`LibxcFunc.GGA_K_GR`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_GR)


            * [`LibxcFunc.GGA_K_LC94`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_LC94)


            * [`LibxcFunc.GGA_K_LIEB`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_LIEB)


            * [`LibxcFunc.GGA_K_LLP`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_LLP)


            * [`LibxcFunc.GGA_K_LUDENA`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_LUDENA)


            * [`LibxcFunc.GGA_K_MEYER`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_MEYER)


            * [`LibxcFunc.GGA_K_OL1`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_OL1)


            * [`LibxcFunc.GGA_K_OL2`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_OL2)


            * [`LibxcFunc.GGA_K_PEARSON`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_PEARSON)


            * [`LibxcFunc.GGA_K_PERDEW`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_PERDEW)


            * [`LibxcFunc.GGA_K_REVAPBE`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_REVAPBE)


            * [`LibxcFunc.GGA_K_REVAPBEINT`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_REVAPBEINT)


            * [`LibxcFunc.GGA_K_TFVW`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_TFVW)


            * [`LibxcFunc.GGA_K_THAKKAR`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_THAKKAR)


            * [`LibxcFunc.GGA_K_TW1`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_TW1)


            * [`LibxcFunc.GGA_K_TW2`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_TW2)


            * [`LibxcFunc.GGA_K_TW3`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_TW3)


            * [`LibxcFunc.GGA_K_TW4`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_TW4)


            * [`LibxcFunc.GGA_K_VJKS`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_VJKS)


            * [`LibxcFunc.GGA_K_VSK`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_VSK)


            * [`LibxcFunc.GGA_K_VW`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_VW)


            * [`LibxcFunc.GGA_K_YT65`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_K_YT65)


            * [`LibxcFunc.GGA_XC_B97_D`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_XC_B97_D)


            * [`LibxcFunc.GGA_XC_B97_GGA1`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_XC_B97_GGA1)


            * [`LibxcFunc.GGA_XC_EDF1`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_XC_EDF1)


            * [`LibxcFunc.GGA_XC_HCTH_120`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_XC_HCTH_120)


            * [`LibxcFunc.GGA_XC_HCTH_147`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_XC_HCTH_147)


            * [`LibxcFunc.GGA_XC_HCTH_407`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_XC_HCTH_407)


            * [`LibxcFunc.GGA_XC_HCTH_407P`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_XC_HCTH_407P)


            * [`LibxcFunc.GGA_XC_HCTH_93`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_XC_HCTH_93)


            * [`LibxcFunc.GGA_XC_HCTH_P14`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_XC_HCTH_P14)


            * [`LibxcFunc.GGA_XC_HCTH_P76`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_XC_HCTH_P76)


            * [`LibxcFunc.GGA_XC_KT2`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_XC_KT2)


            * [`LibxcFunc.GGA_XC_MOHLYP`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_XC_MOHLYP)


            * [`LibxcFunc.GGA_XC_MOHLYP2`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_XC_MOHLYP2)


            * [`LibxcFunc.GGA_XC_MPWLYP1W`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_XC_MPWLYP1W)


            * [`LibxcFunc.GGA_XC_OBLYP_D`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_XC_OBLYP_D)


            * [`LibxcFunc.GGA_XC_OPBE_D`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_XC_OPBE_D)


            * [`LibxcFunc.GGA_XC_OPWLYP_D`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_XC_OPWLYP_D)


            * [`LibxcFunc.GGA_XC_PBE1W`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_XC_PBE1W)


            * [`LibxcFunc.GGA_XC_PBELYP1W`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_XC_PBELYP1W)


            * [`LibxcFunc.GGA_XC_TH1`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_XC_TH1)


            * [`LibxcFunc.GGA_XC_TH2`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_XC_TH2)


            * [`LibxcFunc.GGA_XC_TH3`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_XC_TH3)


            * [`LibxcFunc.GGA_XC_TH4`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_XC_TH4)


            * [`LibxcFunc.GGA_XC_TH_FC`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_XC_TH_FC)


            * [`LibxcFunc.GGA_XC_TH_FCFO`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_XC_TH_FCFO)


            * [`LibxcFunc.GGA_XC_TH_FCO`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_XC_TH_FCO)


            * [`LibxcFunc.GGA_XC_TH_FL`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_XC_TH_FL)


            * [`LibxcFunc.GGA_XC_VV10`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_XC_VV10)


            * [`LibxcFunc.GGA_XC_XLYP`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_XC_XLYP)


            * [`LibxcFunc.GGA_X_2D_B86`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_2D_B86)


            * [`LibxcFunc.GGA_X_2D_B86_MGC`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_2D_B86_MGC)


            * [`LibxcFunc.GGA_X_2D_B88`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_2D_B88)


            * [`LibxcFunc.GGA_X_2D_PBE`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_2D_PBE)


            * [`LibxcFunc.GGA_X_AIRY`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_AIRY)


            * [`LibxcFunc.GGA_X_AK13`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_AK13)


            * [`LibxcFunc.GGA_X_AM05`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_AM05)


            * [`LibxcFunc.GGA_X_APBE`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_APBE)


            * [`LibxcFunc.GGA_X_B86`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_B86)


            * [`LibxcFunc.GGA_X_B86_MGC`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_B86_MGC)


            * [`LibxcFunc.GGA_X_B86_R`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_B86_R)


            * [`LibxcFunc.GGA_X_B88`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_B88)


            * [`LibxcFunc.GGA_X_BAYESIAN`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_BAYESIAN)


            * [`LibxcFunc.GGA_X_BGCP`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_BGCP)


            * [`LibxcFunc.GGA_X_BPCCAC`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_BPCCAC)


            * [`LibxcFunc.GGA_X_C09X`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_C09X)


            * [`LibxcFunc.GGA_X_CAP`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_CAP)


            * [`LibxcFunc.GGA_X_DK87_R1`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_DK87_R1)


            * [`LibxcFunc.GGA_X_DK87_R2`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_DK87_R2)


            * [`LibxcFunc.GGA_X_EV93`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_EV93)


            * [`LibxcFunc.GGA_X_FT97_A`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_FT97_A)


            * [`LibxcFunc.GGA_X_FT97_B`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_FT97_B)


            * [`LibxcFunc.GGA_X_G96`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_G96)


            * [`LibxcFunc.GGA_X_GAM`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_GAM)


            * [`LibxcFunc.GGA_X_HCTH_A`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_HCTH_A)


            * [`LibxcFunc.GGA_X_HERMAN`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_HERMAN)


            * [`LibxcFunc.GGA_X_HJS_B88`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_HJS_B88)


            * [`LibxcFunc.GGA_X_HJS_B88_V2`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_HJS_B88_V2)


            * [`LibxcFunc.GGA_X_HJS_B97X`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_HJS_B97X)


            * [`LibxcFunc.GGA_X_HJS_PBE`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_HJS_PBE)


            * [`LibxcFunc.GGA_X_HJS_PBE_SOL`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_HJS_PBE_SOL)


            * [`LibxcFunc.GGA_X_HTBS`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_HTBS)


            * [`LibxcFunc.GGA_X_ITYH`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_ITYH)


            * [`LibxcFunc.GGA_X_KT1`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_KT1)


            * [`LibxcFunc.GGA_X_LAG`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_LAG)


            * [`LibxcFunc.GGA_X_LAMBDA_CH_N`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_LAMBDA_CH_N)


            * [`LibxcFunc.GGA_X_LAMBDA_LO_N`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_LAMBDA_LO_N)


            * [`LibxcFunc.GGA_X_LAMBDA_OC2_N`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_LAMBDA_OC2_N)


            * [`LibxcFunc.GGA_X_LB`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_LB)


            * [`LibxcFunc.GGA_X_LBM`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_LBM)


            * [`LibxcFunc.GGA_X_LG93`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_LG93)


            * [`LibxcFunc.GGA_X_LV_RPW86`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_LV_RPW86)


            * [`LibxcFunc.GGA_X_MB88`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_MB88)


            * [`LibxcFunc.GGA_X_MPBE`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_MPBE)


            * [`LibxcFunc.GGA_X_MPW91`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_MPW91)


            * [`LibxcFunc.GGA_X_N12`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_N12)


            * [`LibxcFunc.GGA_X_OL2`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_OL2)


            * [`LibxcFunc.GGA_X_OPTB88_VDW`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_OPTB88_VDW)


            * [`LibxcFunc.GGA_X_OPTPBE_VDW`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_OPTPBE_VDW)


            * [`LibxcFunc.GGA_X_OPTX`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_OPTX)


            * [`LibxcFunc.GGA_X_PBE`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_PBE)


            * [`LibxcFunc.GGA_X_PBEA`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_PBEA)


            * [`LibxcFunc.GGA_X_PBEFE`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_PBEFE)


            * [`LibxcFunc.GGA_X_PBEINT`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_PBEINT)


            * [`LibxcFunc.GGA_X_PBEK1_VDW`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_PBEK1_VDW)


            * [`LibxcFunc.GGA_X_PBE_JSJR`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_PBE_JSJR)


            * [`LibxcFunc.GGA_X_PBE_MOL`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_PBE_MOL)


            * [`LibxcFunc.GGA_X_PBE_R`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_PBE_R)


            * [`LibxcFunc.GGA_X_PBE_SOL`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_PBE_SOL)


            * [`LibxcFunc.GGA_X_PBE_TCA`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_PBE_TCA)


            * [`LibxcFunc.GGA_X_PW86`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_PW86)


            * [`LibxcFunc.GGA_X_PW91`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_PW91)


            * [`LibxcFunc.GGA_X_Q2D`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_Q2D)


            * [`LibxcFunc.GGA_X_RGE2`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_RGE2)


            * [`LibxcFunc.GGA_X_RPBE`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_RPBE)


            * [`LibxcFunc.GGA_X_RPW86`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_RPW86)


            * [`LibxcFunc.GGA_X_SFAT`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_SFAT)


            * [`LibxcFunc.GGA_X_SOGGA`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_SOGGA)


            * [`LibxcFunc.GGA_X_SOGGA11`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_SOGGA11)


            * [`LibxcFunc.GGA_X_SSB`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_SSB)


            * [`LibxcFunc.GGA_X_SSB_D`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_SSB_D)


            * [`LibxcFunc.GGA_X_SSB_SW`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_SSB_SW)


            * [`LibxcFunc.GGA_X_VMT84_GE`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_VMT84_GE)


            * [`LibxcFunc.GGA_X_VMT84_PBE`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_VMT84_PBE)


            * [`LibxcFunc.GGA_X_VMT_GE`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_VMT_GE)


            * [`LibxcFunc.GGA_X_VMT_PBE`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_VMT_PBE)


            * [`LibxcFunc.GGA_X_WC`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_WC)


            * [`LibxcFunc.GGA_X_WPBEH`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_WPBEH)


            * [`LibxcFunc.GGA_X_XPBE`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.GGA_X_XPBE)


            * [`LibxcFunc.HYB_GGA_XC_B1LYP`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_B1LYP)


            * [`LibxcFunc.HYB_GGA_XC_B1PW91`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_B1PW91)


            * [`LibxcFunc.HYB_GGA_XC_B1WC`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_B1WC)


            * [`LibxcFunc.HYB_GGA_XC_B3LYP`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_B3LYP)


            * [`LibxcFunc.HYB_GGA_XC_B3LYP5`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_B3LYP5)


            * [`LibxcFunc.HYB_GGA_XC_B3LYPs`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_B3LYPs)


            * [`LibxcFunc.HYB_GGA_XC_B3P86`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_B3P86)


            * [`LibxcFunc.HYB_GGA_XC_B3PW91`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_B3PW91)


            * [`LibxcFunc.HYB_GGA_XC_B97`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_B97)


            * [`LibxcFunc.HYB_GGA_XC_B97_1`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_B97_1)


            * [`LibxcFunc.HYB_GGA_XC_B97_1p`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_B97_1p)


            * [`LibxcFunc.HYB_GGA_XC_B97_2`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_B97_2)


            * [`LibxcFunc.HYB_GGA_XC_B97_3`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_B97_3)


            * [`LibxcFunc.HYB_GGA_XC_B97_K`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_B97_K)


            * [`LibxcFunc.HYB_GGA_XC_BHANDH`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_BHANDH)


            * [`LibxcFunc.HYB_GGA_XC_BHANDHLYP`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_BHANDHLYP)


            * [`LibxcFunc.HYB_GGA_XC_CAMY_B3LYP`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_CAMY_B3LYP)


            * [`LibxcFunc.HYB_GGA_XC_CAMY_BLYP`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_CAMY_BLYP)


            * [`LibxcFunc.HYB_GGA_XC_CAM_B3LYP`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_CAM_B3LYP)


            * [`LibxcFunc.HYB_GGA_XC_CAP0`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_CAP0)


            * [`LibxcFunc.HYB_GGA_XC_EDF2`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_EDF2)


            * [`LibxcFunc.HYB_GGA_XC_HJS_B88`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_HJS_B88)


            * [`LibxcFunc.HYB_GGA_XC_HJS_B97X`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_HJS_B97X)


            * [`LibxcFunc.HYB_GGA_XC_HJS_PBE`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_HJS_PBE)


            * [`LibxcFunc.HYB_GGA_XC_HJS_PBE_SOL`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_HJS_PBE_SOL)


            * [`LibxcFunc.HYB_GGA_XC_HPBEINT`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_HPBEINT)


            * [`LibxcFunc.HYB_GGA_XC_HSE03`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_HSE03)


            * [`LibxcFunc.HYB_GGA_XC_HSE06`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_HSE06)


            * [`LibxcFunc.HYB_GGA_XC_LCY_BLYP`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_LCY_BLYP)


            * [`LibxcFunc.HYB_GGA_XC_LCY_PBE`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_LCY_PBE)


            * [`LibxcFunc.HYB_GGA_XC_LC_VV10`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_LC_VV10)


            * [`LibxcFunc.HYB_GGA_XC_LRC_WPBE`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_LRC_WPBE)


            * [`LibxcFunc.HYB_GGA_XC_LRC_WPBEH`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_LRC_WPBEH)


            * [`LibxcFunc.HYB_GGA_XC_MB3LYP_RC04`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_MB3LYP_RC04)


            * [`LibxcFunc.HYB_GGA_XC_MPW3LYP`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_MPW3LYP)


            * [`LibxcFunc.HYB_GGA_XC_MPW3PW`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_MPW3PW)


            * [`LibxcFunc.HYB_GGA_XC_MPWLYP1M`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_MPWLYP1M)


            * [`LibxcFunc.HYB_GGA_XC_O3LYP`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_O3LYP)


            * [`LibxcFunc.HYB_GGA_XC_PBE0_13`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_PBE0_13)


            * [`LibxcFunc.HYB_GGA_XC_PBEH`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_PBEH)


            * [`LibxcFunc.HYB_GGA_XC_REVB3LYP`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_REVB3LYP)


            * [`LibxcFunc.HYB_GGA_XC_SB98_1a`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_SB98_1a)


            * [`LibxcFunc.HYB_GGA_XC_SB98_1b`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_SB98_1b)


            * [`LibxcFunc.HYB_GGA_XC_SB98_1c`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_SB98_1c)


            * [`LibxcFunc.HYB_GGA_XC_SB98_2a`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_SB98_2a)


            * [`LibxcFunc.HYB_GGA_XC_SB98_2b`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_SB98_2b)


            * [`LibxcFunc.HYB_GGA_XC_SB98_2c`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_SB98_2c)


            * [`LibxcFunc.HYB_GGA_XC_TUNED_CAM_B3LYP`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_TUNED_CAM_B3LYP)


            * [`LibxcFunc.HYB_GGA_XC_WB97`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_WB97)


            * [`LibxcFunc.HYB_GGA_XC_WB97X`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_WB97X)


            * [`LibxcFunc.HYB_GGA_XC_WB97X_D`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_WB97X_D)


            * [`LibxcFunc.HYB_GGA_XC_WB97X_V`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_WB97X_V)


            * [`LibxcFunc.HYB_GGA_XC_X3LYP`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_X3LYP)


            * [`LibxcFunc.HYB_GGA_XC_mPW1K`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_mPW1K)


            * [`LibxcFunc.HYB_GGA_XC_mPW1PW`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_XC_mPW1PW)


            * [`LibxcFunc.HYB_GGA_X_N12_SX`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_X_N12_SX)


            * [`LibxcFunc.HYB_GGA_X_SOGGA11_X`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_GGA_X_SOGGA11_X)


            * [`LibxcFunc.HYB_MGGA_XC_B86B95`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_MGGA_XC_B86B95)


            * [`LibxcFunc.HYB_MGGA_XC_B88B95`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_MGGA_XC_B88B95)


            * [`LibxcFunc.HYB_MGGA_XC_BB1K`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_MGGA_XC_BB1K)


            * [`LibxcFunc.HYB_MGGA_XC_M05`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_MGGA_XC_M05)


            * [`LibxcFunc.HYB_MGGA_XC_M05_2X`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_MGGA_XC_M05_2X)


            * [`LibxcFunc.HYB_MGGA_XC_M06`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_MGGA_XC_M06)


            * [`LibxcFunc.HYB_MGGA_XC_M06_2X`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_MGGA_XC_M06_2X)


            * [`LibxcFunc.HYB_MGGA_XC_M06_HF`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_MGGA_XC_M06_HF)


            * [`LibxcFunc.HYB_MGGA_XC_M08_HX`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_MGGA_XC_M08_HX)


            * [`LibxcFunc.HYB_MGGA_XC_M08_SO`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_MGGA_XC_M08_SO)


            * [`LibxcFunc.HYB_MGGA_XC_M11`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_MGGA_XC_M11)


            * [`LibxcFunc.HYB_MGGA_XC_MPW1B95`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_MGGA_XC_MPW1B95)


            * [`LibxcFunc.HYB_MGGA_XC_MPWB1K`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_MGGA_XC_MPWB1K)


            * [`LibxcFunc.HYB_MGGA_XC_PW6B95`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_MGGA_XC_PW6B95)


            * [`LibxcFunc.HYB_MGGA_XC_PW86B95`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_MGGA_XC_PW86B95)


            * [`LibxcFunc.HYB_MGGA_XC_PWB6K`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_MGGA_XC_PWB6K)


            * [`LibxcFunc.HYB_MGGA_XC_REVTPSSH`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_MGGA_XC_REVTPSSH)


            * [`LibxcFunc.HYB_MGGA_XC_TPSSH`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_MGGA_XC_TPSSH)


            * [`LibxcFunc.HYB_MGGA_XC_WB97M_V`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_MGGA_XC_WB97M_V)


            * [`LibxcFunc.HYB_MGGA_XC_X1B95`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_MGGA_XC_X1B95)


            * [`LibxcFunc.HYB_MGGA_XC_XB1K`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_MGGA_XC_XB1K)


            * [`LibxcFunc.HYB_MGGA_X_DLDF`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_MGGA_X_DLDF)


            * [`LibxcFunc.HYB_MGGA_X_MN12_SX`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_MGGA_X_MN12_SX)


            * [`LibxcFunc.HYB_MGGA_X_MN15`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_MGGA_X_MN15)


            * [`LibxcFunc.HYB_MGGA_X_MS2H`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_MGGA_X_MS2H)


            * [`LibxcFunc.HYB_MGGA_X_MVSH`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_MGGA_X_MVSH)


            * [`LibxcFunc.HYB_MGGA_X_SCAN0`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.HYB_MGGA_X_SCAN0)


            * [`LibxcFunc.LDA_C_1D_CSC`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_C_1D_CSC)


            * [`LibxcFunc.LDA_C_1D_LOOS`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_C_1D_LOOS)


            * [`LibxcFunc.LDA_C_2D_AMGB`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_C_2D_AMGB)


            * [`LibxcFunc.LDA_C_2D_PRM`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_C_2D_PRM)


            * [`LibxcFunc.LDA_C_GL`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_C_GL)


            * [`LibxcFunc.LDA_C_GOMBAS`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_C_GOMBAS)


            * [`LibxcFunc.LDA_C_HL`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_C_HL)


            * [`LibxcFunc.LDA_C_ML1`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_C_ML1)


            * [`LibxcFunc.LDA_C_ML2`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_C_ML2)


            * [`LibxcFunc.LDA_C_OB_PW`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_C_OB_PW)


            * [`LibxcFunc.LDA_C_OB_PZ`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_C_OB_PZ)


            * [`LibxcFunc.LDA_C_PW`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_C_PW)


            * [`LibxcFunc.LDA_C_PW_MOD`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_C_PW_MOD)


            * [`LibxcFunc.LDA_C_PW_RPA`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_C_PW_RPA)


            * [`LibxcFunc.LDA_C_PZ`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_C_PZ)


            * [`LibxcFunc.LDA_C_PZ_MOD`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_C_PZ_MOD)


            * [`LibxcFunc.LDA_C_RC04`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_C_RC04)


            * [`LibxcFunc.LDA_C_RPA`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_C_RPA)


            * [`LibxcFunc.LDA_C_VWN`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_C_VWN)


            * [`LibxcFunc.LDA_C_VWN_1`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_C_VWN_1)


            * [`LibxcFunc.LDA_C_VWN_2`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_C_VWN_2)


            * [`LibxcFunc.LDA_C_VWN_3`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_C_VWN_3)


            * [`LibxcFunc.LDA_C_VWN_4`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_C_VWN_4)


            * [`LibxcFunc.LDA_C_VWN_RPA`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_C_VWN_RPA)


            * [`LibxcFunc.LDA_C_WIGNER`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_C_WIGNER)


            * [`LibxcFunc.LDA_C_XALPHA`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_C_XALPHA)


            * [`LibxcFunc.LDA_C_vBH`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_C_vBH)


            * [`LibxcFunc.LDA_K_LP`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_K_LP)


            * [`LibxcFunc.LDA_K_TF`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_K_TF)


            * [`LibxcFunc.LDA_X`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_X)


            * [`LibxcFunc.LDA_XC_KSDT`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_XC_KSDT)


            * [`LibxcFunc.LDA_XC_TETER93`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_XC_TETER93)


            * [`LibxcFunc.LDA_XC_ZLP`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_XC_ZLP)


            * [`LibxcFunc.LDA_X_1D`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_X_1D)


            * [`LibxcFunc.LDA_X_2D`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.LDA_X_2D)


            * [`LibxcFunc.MGGA_C_BC95`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_C_BC95)


            * [`LibxcFunc.MGGA_C_CC06`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_C_CC06)


            * [`LibxcFunc.MGGA_C_CS`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_C_CS)


            * [`LibxcFunc.MGGA_C_DLDF`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_C_DLDF)


            * [`LibxcFunc.MGGA_C_M05`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_C_M05)


            * [`LibxcFunc.MGGA_C_M05_2X`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_C_M05_2X)


            * [`LibxcFunc.MGGA_C_M06`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_C_M06)


            * [`LibxcFunc.MGGA_C_M06_2X`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_C_M06_2X)


            * [`LibxcFunc.MGGA_C_M06_HF`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_C_M06_HF)


            * [`LibxcFunc.MGGA_C_M06_L`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_C_M06_L)


            * [`LibxcFunc.MGGA_C_M08_HX`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_C_M08_HX)


            * [`LibxcFunc.MGGA_C_M08_SO`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_C_M08_SO)


            * [`LibxcFunc.MGGA_C_M11`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_C_M11)


            * [`LibxcFunc.MGGA_C_M11_L`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_C_M11_L)


            * [`LibxcFunc.MGGA_C_MN12_L`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_C_MN12_L)


            * [`LibxcFunc.MGGA_C_MN12_SX`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_C_MN12_SX)


            * [`LibxcFunc.MGGA_C_MN15`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_C_MN15)


            * [`LibxcFunc.MGGA_C_MN15_L`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_C_MN15_L)


            * [`LibxcFunc.MGGA_C_PKZB`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_C_PKZB)


            * [`LibxcFunc.MGGA_C_REVTPSS`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_C_REVTPSS)


            * [`LibxcFunc.MGGA_C_SCAN`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_C_SCAN)


            * [`LibxcFunc.MGGA_C_TPSS`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_C_TPSS)


            * [`LibxcFunc.MGGA_C_TPSSLOC`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_C_TPSSLOC)


            * [`LibxcFunc.MGGA_C_VSXC`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_C_VSXC)


            * [`LibxcFunc.MGGA_XC_B97M_V`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_XC_B97M_V)


            * [`LibxcFunc.MGGA_XC_OTPSS_D`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_XC_OTPSS_D)


            * [`LibxcFunc.MGGA_XC_TPSSLYP1W`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_XC_TPSSLYP1W)


            * [`LibxcFunc.MGGA_XC_ZLP`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_XC_ZLP)


            * [`LibxcFunc.MGGA_X_2D_PRHG07`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_2D_PRHG07)


            * [`LibxcFunc.MGGA_X_2D_PRHG07_PRP10`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_2D_PRHG07_PRP10)


            * [`LibxcFunc.MGGA_X_BJ06`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_BJ06)


            * [`LibxcFunc.MGGA_X_BLOC`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_BLOC)


            * [`LibxcFunc.MGGA_X_BR89`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_BR89)


            * [`LibxcFunc.MGGA_X_GVT4`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_GVT4)


            * [`LibxcFunc.MGGA_X_LTA`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_LTA)


            * [`LibxcFunc.MGGA_X_M05`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_M05)


            * [`LibxcFunc.MGGA_X_M05_2X`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_M05_2X)


            * [`LibxcFunc.MGGA_X_M06`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_M06)


            * [`LibxcFunc.MGGA_X_M06_2X`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_M06_2X)


            * [`LibxcFunc.MGGA_X_M06_HF`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_M06_HF)


            * [`LibxcFunc.MGGA_X_M06_L`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_M06_L)


            * [`LibxcFunc.MGGA_X_M08_HX`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_M08_HX)


            * [`LibxcFunc.MGGA_X_M08_SO`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_M08_SO)


            * [`LibxcFunc.MGGA_X_M11`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_M11)


            * [`LibxcFunc.MGGA_X_M11_L`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_M11_L)


            * [`LibxcFunc.MGGA_X_MBEEF`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_MBEEF)


            * [`LibxcFunc.MGGA_X_MBEEFVDW`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_MBEEFVDW)


            * [`LibxcFunc.MGGA_X_MK00`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_MK00)


            * [`LibxcFunc.MGGA_X_MK00B`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_MK00B)


            * [`LibxcFunc.MGGA_X_MN12_L`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_MN12_L)


            * [`LibxcFunc.MGGA_X_MN15_L`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_MN15_L)


            * [`LibxcFunc.MGGA_X_MODTPSS`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_MODTPSS)


            * [`LibxcFunc.MGGA_X_MS0`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_MS0)


            * [`LibxcFunc.MGGA_X_MS1`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_MS1)


            * [`LibxcFunc.MGGA_X_MS2`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_MS2)


            * [`LibxcFunc.MGGA_X_MVS`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_MVS)


            * [`LibxcFunc.MGGA_X_PKZB`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_PKZB)


            * [`LibxcFunc.MGGA_X_REVTPSS`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_REVTPSS)


            * [`LibxcFunc.MGGA_X_RPP09`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_RPP09)


            * [`LibxcFunc.MGGA_X_SCAN`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_SCAN)


            * [`LibxcFunc.MGGA_X_TAU_HCTH`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_TAU_HCTH)


            * [`LibxcFunc.MGGA_X_TB09`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_TB09)


            * [`LibxcFunc.MGGA_X_TPSS`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.MGGA_X_TPSS)


            * [`LibxcFunc.all_families()`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.all_families)


            * [`LibxcFunc.all_kinds()`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.all_kinds)


            * [`LibxcFunc.as_dict()`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.as_dict)


            * [`LibxcFunc.from_dict()`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.from_dict)


            * [`LibxcFunc.info_dict`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.info_dict)


            * [`LibxcFunc.is_c_kind`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.is_c_kind)


            * [`LibxcFunc.is_gga_family`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.is_gga_family)


            * [`LibxcFunc.is_hyb_gga_family`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.is_hyb_gga_family)


            * [`LibxcFunc.is_hyb_mgga_family`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.is_hyb_mgga_family)


            * [`LibxcFunc.is_k_kind`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.is_k_kind)


            * [`LibxcFunc.is_lda_family`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.is_lda_family)


            * [`LibxcFunc.is_mgga_family`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.is_mgga_family)


            * [`LibxcFunc.is_x_kind`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.is_x_kind)


            * [`LibxcFunc.is_xc_kind`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.is_xc_kind)


            * [`LibxcFunc.to_json()`](pymatgen.core.md#pymatgen.core.libxcfunc.LibxcFunc.to_json)


    * [pymatgen.core.molecular_orbitals module](pymatgen.core.md#module-pymatgen.core.molecular_orbitals)


        * [`MolecularOrbitals`](pymatgen.core.md#pymatgen.core.molecular_orbitals.MolecularOrbitals)


            * [`MolecularOrbitals.composition`](pymatgen.core.md#pymatgen.core.molecular_orbitals.MolecularOrbitals.composition)


            * [`MolecularOrbitals.elements`](pymatgen.core.md#pymatgen.core.molecular_orbitals.MolecularOrbitals.elements)


            * [`MolecularOrbitals.elec_neg`](pymatgen.core.md#pymatgen.core.molecular_orbitals.MolecularOrbitals.elec_neg)


            * [`MolecularOrbitals.aos`](pymatgen.core.md#pymatgen.core.molecular_orbitals.MolecularOrbitals.aos)


            * [`MolecularOrbitals.band_edges`](pymatgen.core.md#pymatgen.core.molecular_orbitals.MolecularOrbitals.band_edges)


            * [`MolecularOrbitals.aos_as_list()`](pymatgen.core.md#pymatgen.core.molecular_orbitals.MolecularOrbitals.aos_as_list)


            * [`MolecularOrbitals.max_electronegativity()`](pymatgen.core.md#pymatgen.core.molecular_orbitals.MolecularOrbitals.max_electronegativity)


            * [`MolecularOrbitals.obtain_band_edges()`](pymatgen.core.md#pymatgen.core.molecular_orbitals.MolecularOrbitals.obtain_band_edges)


    * [pymatgen.core.operations module](pymatgen.core.md#module-pymatgen.core.operations)


        * [`MagSymmOp`](pymatgen.core.md#pymatgen.core.operations.MagSymmOp)


            * [`MagSymmOp.as_dict()`](pymatgen.core.md#pymatgen.core.operations.MagSymmOp.as_dict)


            * [`MagSymmOp.as_xyzt_str()`](pymatgen.core.md#pymatgen.core.operations.MagSymmOp.as_xyzt_str)


            * [`MagSymmOp.as_xyzt_string()`](pymatgen.core.md#pymatgen.core.operations.MagSymmOp.as_xyzt_string)


            * [`MagSymmOp.from_dict()`](pymatgen.core.md#pymatgen.core.operations.MagSymmOp.from_dict)


            * [`MagSymmOp.from_rotation_and_translation_and_time_reversal()`](pymatgen.core.md#pymatgen.core.operations.MagSymmOp.from_rotation_and_translation_and_time_reversal)


            * [`MagSymmOp.from_symmop()`](pymatgen.core.md#pymatgen.core.operations.MagSymmOp.from_symmop)


            * [`MagSymmOp.from_xyzt_str()`](pymatgen.core.md#pymatgen.core.operations.MagSymmOp.from_xyzt_str)


            * [`MagSymmOp.from_xyzt_string()`](pymatgen.core.md#pymatgen.core.operations.MagSymmOp.from_xyzt_string)


            * [`MagSymmOp.operate_magmom()`](pymatgen.core.md#pymatgen.core.operations.MagSymmOp.operate_magmom)


        * [`SymmOp`](pymatgen.core.md#pymatgen.core.operations.SymmOp)


            * [`SymmOp.affine_matrix`](pymatgen.core.md#pymatgen.core.operations.SymmOp.affine_matrix)


            * [`SymmOp.apply_rotation_only()`](pymatgen.core.md#pymatgen.core.operations.SymmOp.apply_rotation_only)


            * [`SymmOp.are_symmetrically_related()`](pymatgen.core.md#pymatgen.core.operations.SymmOp.are_symmetrically_related)


            * [`SymmOp.are_symmetrically_related_vectors()`](pymatgen.core.md#pymatgen.core.operations.SymmOp.are_symmetrically_related_vectors)


            * [`SymmOp.as_dict()`](pymatgen.core.md#pymatgen.core.operations.SymmOp.as_dict)


            * [`SymmOp.as_xyz_str()`](pymatgen.core.md#pymatgen.core.operations.SymmOp.as_xyz_str)


            * [`SymmOp.as_xyz_string()`](pymatgen.core.md#pymatgen.core.operations.SymmOp.as_xyz_string)


            * [`SymmOp.from_axis_angle_and_translation()`](pymatgen.core.md#pymatgen.core.operations.SymmOp.from_axis_angle_and_translation)


            * [`SymmOp.from_dict()`](pymatgen.core.md#pymatgen.core.operations.SymmOp.from_dict)


            * [`SymmOp.from_origin_axis_angle()`](pymatgen.core.md#pymatgen.core.operations.SymmOp.from_origin_axis_angle)


            * [`SymmOp.from_rotation_and_translation()`](pymatgen.core.md#pymatgen.core.operations.SymmOp.from_rotation_and_translation)


            * [`SymmOp.from_xyz_str()`](pymatgen.core.md#pymatgen.core.operations.SymmOp.from_xyz_str)


            * [`SymmOp.from_xyz_string()`](pymatgen.core.md#pymatgen.core.operations.SymmOp.from_xyz_string)


            * [`SymmOp.inverse`](pymatgen.core.md#pymatgen.core.operations.SymmOp.inverse)


            * [`SymmOp.inversion()`](pymatgen.core.md#pymatgen.core.operations.SymmOp.inversion)


            * [`SymmOp.operate()`](pymatgen.core.md#pymatgen.core.operations.SymmOp.operate)


            * [`SymmOp.operate_multi()`](pymatgen.core.md#pymatgen.core.operations.SymmOp.operate_multi)


            * [`SymmOp.reflection()`](pymatgen.core.md#pymatgen.core.operations.SymmOp.reflection)


            * [`SymmOp.rotation_matrix`](pymatgen.core.md#pymatgen.core.operations.SymmOp.rotation_matrix)


            * [`SymmOp.rotoreflection()`](pymatgen.core.md#pymatgen.core.operations.SymmOp.rotoreflection)


            * [`SymmOp.transform_tensor()`](pymatgen.core.md#pymatgen.core.operations.SymmOp.transform_tensor)


            * [`SymmOp.translation_vector`](pymatgen.core.md#pymatgen.core.operations.SymmOp.translation_vector)


    * [pymatgen.core.periodic_table module](pymatgen.core.md#module-pymatgen.core.periodic_table)


        * [`DummySpecie`](pymatgen.core.md#pymatgen.core.periodic_table.DummySpecie)


        * [`DummySpecies`](pymatgen.core.md#pymatgen.core.periodic_table.DummySpecies)


            * [`DummySpecies.oxi_state`](pymatgen.core.md#pymatgen.core.periodic_table.DummySpecies.oxi_state)


            * [`DummySpecies.Z`](pymatgen.core.md#pymatgen.core.periodic_table.DummySpecies.Z)


            * [`DummySpecies.X`](pymatgen.core.md#pymatgen.core.periodic_table.DummySpecies.X)


            * [`DummySpecies.X`](pymatgen.core.md#id0)


            * [`DummySpecies.Z`](pymatgen.core.md#id1)


            * [`DummySpecies.as_dict()`](pymatgen.core.md#pymatgen.core.periodic_table.DummySpecies.as_dict)


            * [`DummySpecies.from_dict()`](pymatgen.core.md#pymatgen.core.periodic_table.DummySpecies.from_dict)


            * [`DummySpecies.from_str()`](pymatgen.core.md#pymatgen.core.periodic_table.DummySpecies.from_str)


            * [`DummySpecies.oxi_state`](pymatgen.core.md#id2)


            * [`DummySpecies.symbol`](pymatgen.core.md#pymatgen.core.periodic_table.DummySpecies.symbol)


        * [`Element`](pymatgen.core.md#pymatgen.core.periodic_table.Element)


            * [`Element.Z`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Z)


            * [`Element.symbol`](pymatgen.core.md#pymatgen.core.periodic_table.Element.symbol)


            * [`Element.long_name`](pymatgen.core.md#pymatgen.core.periodic_table.Element.long_name)


            * [`Element.atomic_radius_calculated`](pymatgen.core.md#pymatgen.core.periodic_table.Element.atomic_radius_calculated)


            * [`Element.van_der_waals_radius`](pymatgen.core.md#pymatgen.core.periodic_table.Element.van_der_waals_radius)


            * [`Element.mendeleev_no`](pymatgen.core.md#pymatgen.core.periodic_table.Element.mendeleev_no)


            * [`Element.electrical_resistivity`](pymatgen.core.md#pymatgen.core.periodic_table.Element.electrical_resistivity)


            * [`Element.velocity_of_sound`](pymatgen.core.md#pymatgen.core.periodic_table.Element.velocity_of_sound)


            * [`Element.reflectivity`](pymatgen.core.md#pymatgen.core.periodic_table.Element.reflectivity)


            * [`Element.refractive_index`](pymatgen.core.md#pymatgen.core.periodic_table.Element.refractive_index)


            * [`Element.poissons_ratio`](pymatgen.core.md#pymatgen.core.periodic_table.Element.poissons_ratio)


            * [`Element.molar_volume`](pymatgen.core.md#pymatgen.core.periodic_table.Element.molar_volume)


            * [`Element.electronic_structure`](pymatgen.core.md#pymatgen.core.periodic_table.Element.electronic_structure)


            * [`Element.atomic_orbitals`](pymatgen.core.md#pymatgen.core.periodic_table.Element.atomic_orbitals)


            * [`Element.thermal_conductivity`](pymatgen.core.md#pymatgen.core.periodic_table.Element.thermal_conductivity)


            * [`Element.boiling_point`](pymatgen.core.md#pymatgen.core.periodic_table.Element.boiling_point)


            * [`Element.melting_point`](pymatgen.core.md#pymatgen.core.periodic_table.Element.melting_point)


            * [`Element.critical_temperature`](pymatgen.core.md#pymatgen.core.periodic_table.Element.critical_temperature)


            * [`Element.superconduction_temperature`](pymatgen.core.md#pymatgen.core.periodic_table.Element.superconduction_temperature)


            * [`Element.liquid_range`](pymatgen.core.md#pymatgen.core.periodic_table.Element.liquid_range)


            * [`Element.bulk_modulus`](pymatgen.core.md#pymatgen.core.periodic_table.Element.bulk_modulus)


            * [`Element.youngs_modulus`](pymatgen.core.md#pymatgen.core.periodic_table.Element.youngs_modulus)


            * [`Element.brinell_hardness`](pymatgen.core.md#pymatgen.core.periodic_table.Element.brinell_hardness)


            * [`Element.rigidity_modulus`](pymatgen.core.md#pymatgen.core.periodic_table.Element.rigidity_modulus)


            * [`Element.mineral_hardness`](pymatgen.core.md#pymatgen.core.periodic_table.Element.mineral_hardness)


            * [`Element.vickers_hardness`](pymatgen.core.md#pymatgen.core.periodic_table.Element.vickers_hardness)


            * [`Element.density_of_solid`](pymatgen.core.md#pymatgen.core.periodic_table.Element.density_of_solid)


            * [`Element.coefficient_of_linear_thermal_expansion`](pymatgen.core.md#pymatgen.core.periodic_table.Element.coefficient_of_linear_thermal_expansion)


            * [`Element.ground_level`](pymatgen.core.md#pymatgen.core.periodic_table.Element.ground_level)


            * [`Element.ionization_energies`](pymatgen.core.md#pymatgen.core.periodic_table.Element.ionization_energies)


            * [`Element.Ac`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Ac)


            * [`Element.Ag`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Ag)


            * [`Element.Al`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Al)


            * [`Element.Am`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Am)


            * [`Element.Ar`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Ar)


            * [`Element.As`](pymatgen.core.md#pymatgen.core.periodic_table.Element.As)


            * [`Element.At`](pymatgen.core.md#pymatgen.core.periodic_table.Element.At)


            * [`Element.Au`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Au)


            * [`Element.B`](pymatgen.core.md#pymatgen.core.periodic_table.Element.B)


            * [`Element.Ba`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Ba)


            * [`Element.Be`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Be)


            * [`Element.Bh`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Bh)


            * [`Element.Bi`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Bi)


            * [`Element.Bk`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Bk)


            * [`Element.Br`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Br)


            * [`Element.C`](pymatgen.core.md#pymatgen.core.periodic_table.Element.C)


            * [`Element.Ca`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Ca)


            * [`Element.Cd`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Cd)


            * [`Element.Ce`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Ce)


            * [`Element.Cf`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Cf)


            * [`Element.Cl`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Cl)


            * [`Element.Cm`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Cm)


            * [`Element.Cn`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Cn)


            * [`Element.Co`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Co)


            * [`Element.Cr`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Cr)


            * [`Element.Cs`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Cs)


            * [`Element.Cu`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Cu)


            * [`Element.Db`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Db)


            * [`Element.Ds`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Ds)


            * [`Element.Dy`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Dy)


            * [`Element.Er`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Er)


            * [`Element.Es`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Es)


            * [`Element.Eu`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Eu)


            * [`Element.F`](pymatgen.core.md#pymatgen.core.periodic_table.Element.F)


            * [`Element.Fe`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Fe)


            * [`Element.Fl`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Fl)


            * [`Element.Fm`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Fm)


            * [`Element.Fr`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Fr)


            * [`Element.Ga`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Ga)


            * [`Element.Gd`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Gd)


            * [`Element.Ge`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Ge)


            * [`Element.H`](pymatgen.core.md#pymatgen.core.periodic_table.Element.H)


            * [`Element.He`](pymatgen.core.md#pymatgen.core.periodic_table.Element.He)


            * [`Element.Hf`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Hf)


            * [`Element.Hg`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Hg)


            * [`Element.Ho`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Ho)


            * [`Element.Hs`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Hs)


            * [`Element.I`](pymatgen.core.md#pymatgen.core.periodic_table.Element.I)


            * [`Element.In`](pymatgen.core.md#pymatgen.core.periodic_table.Element.In)


            * [`Element.Ir`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Ir)


            * [`Element.K`](pymatgen.core.md#pymatgen.core.periodic_table.Element.K)


            * [`Element.Kr`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Kr)


            * [`Element.La`](pymatgen.core.md#pymatgen.core.periodic_table.Element.La)


            * [`Element.Li`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Li)


            * [`Element.Lr`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Lr)


            * [`Element.Lu`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Lu)


            * [`Element.Lv`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Lv)


            * [`Element.Mc`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Mc)


            * [`Element.Md`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Md)


            * [`Element.Mg`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Mg)


            * [`Element.Mn`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Mn)


            * [`Element.Mo`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Mo)


            * [`Element.Mt`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Mt)


            * [`Element.N`](pymatgen.core.md#pymatgen.core.periodic_table.Element.N)


            * [`Element.Na`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Na)


            * [`Element.Nb`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Nb)


            * [`Element.Nd`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Nd)


            * [`Element.Ne`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Ne)


            * [`Element.Nh`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Nh)


            * [`Element.Ni`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Ni)


            * [`Element.No`](pymatgen.core.md#pymatgen.core.periodic_table.Element.No)


            * [`Element.Np`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Np)


            * [`Element.O`](pymatgen.core.md#pymatgen.core.periodic_table.Element.O)


            * [`Element.Og`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Og)


            * [`Element.Os`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Os)


            * [`Element.P`](pymatgen.core.md#pymatgen.core.periodic_table.Element.P)


            * [`Element.Pa`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Pa)


            * [`Element.Pb`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Pb)


            * [`Element.Pd`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Pd)


            * [`Element.Pm`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Pm)


            * [`Element.Po`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Po)


            * [`Element.Pr`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Pr)


            * [`Element.Pt`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Pt)


            * [`Element.Pu`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Pu)


            * [`Element.Ra`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Ra)


            * [`Element.Rb`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Rb)


            * [`Element.Re`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Re)


            * [`Element.Rf`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Rf)


            * [`Element.Rg`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Rg)


            * [`Element.Rh`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Rh)


            * [`Element.Rn`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Rn)


            * [`Element.Ru`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Ru)


            * [`Element.S`](pymatgen.core.md#pymatgen.core.periodic_table.Element.S)


            * [`Element.Sb`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Sb)


            * [`Element.Sc`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Sc)


            * [`Element.Se`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Se)


            * [`Element.Sg`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Sg)


            * [`Element.Si`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Si)


            * [`Element.Sm`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Sm)


            * [`Element.Sn`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Sn)


            * [`Element.Sr`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Sr)


            * [`Element.Ta`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Ta)


            * [`Element.Tb`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Tb)


            * [`Element.Tc`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Tc)


            * [`Element.Te`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Te)


            * [`Element.Th`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Th)


            * [`Element.Ti`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Ti)


            * [`Element.Tl`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Tl)


            * [`Element.Tm`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Tm)


            * [`Element.Ts`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Ts)


            * [`Element.U`](pymatgen.core.md#pymatgen.core.periodic_table.Element.U)


            * [`Element.V`](pymatgen.core.md#pymatgen.core.periodic_table.Element.V)


            * [`Element.W`](pymatgen.core.md#pymatgen.core.periodic_table.Element.W)


            * [`Element.Xe`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Xe)


            * [`Element.Y`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Y)


            * [`Element.Yb`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Yb)


            * [`Element.Zn`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Zn)


            * [`Element.Zr`](pymatgen.core.md#pymatgen.core.periodic_table.Element.Zr)


        * [`ElementBase`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase)


            * [`ElementBase.Z`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.Z)


            * [`ElementBase.symbol`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.symbol)


            * [`ElementBase.long_name`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.long_name)


            * [`ElementBase.atomic_radius_calculated`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.atomic_radius_calculated)


            * [`ElementBase.van_der_waals_radius`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.van_der_waals_radius)


            * [`ElementBase.mendeleev_no`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.mendeleev_no)


            * [`ElementBase.electrical_resistivity`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.electrical_resistivity)


            * [`ElementBase.velocity_of_sound`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.velocity_of_sound)


            * [`ElementBase.reflectivity`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.reflectivity)


            * [`ElementBase.refractive_index`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.refractive_index)


            * [`ElementBase.poissons_ratio`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.poissons_ratio)


            * [`ElementBase.molar_volume`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.molar_volume)


            * [`ElementBase.electronic_structure`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.electronic_structure)


            * [`ElementBase.atomic_orbitals`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.atomic_orbitals)


            * [`ElementBase.thermal_conductivity`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.thermal_conductivity)


            * [`ElementBase.boiling_point`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.boiling_point)


            * [`ElementBase.melting_point`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.melting_point)


            * [`ElementBase.critical_temperature`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.critical_temperature)


            * [`ElementBase.superconduction_temperature`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.superconduction_temperature)


            * [`ElementBase.liquid_range`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.liquid_range)


            * [`ElementBase.bulk_modulus`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.bulk_modulus)


            * [`ElementBase.youngs_modulus`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.youngs_modulus)


            * [`ElementBase.brinell_hardness`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.brinell_hardness)


            * [`ElementBase.rigidity_modulus`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.rigidity_modulus)


            * [`ElementBase.mineral_hardness`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.mineral_hardness)


            * [`ElementBase.vickers_hardness`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.vickers_hardness)


            * [`ElementBase.density_of_solid`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.density_of_solid)


            * [`ElementBase.coefficient_of_linear_thermal_expansion`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.coefficient_of_linear_thermal_expansion)


            * [`ElementBase.ground_level`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.ground_level)


            * [`ElementBase.ionization_energies`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.ionization_energies)


            * [`ElementBase.X`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.X)


            * [`ElementBase.as_dict()`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.as_dict)


            * [`ElementBase.atomic_mass`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.atomic_mass)


            * [`ElementBase.atomic_radius`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.atomic_radius)


            * [`ElementBase.average_anionic_radius`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.average_anionic_radius)


            * [`ElementBase.average_cationic_radius`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.average_cationic_radius)


            * [`ElementBase.average_ionic_radius`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.average_ionic_radius)


            * [`ElementBase.block`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.block)


            * [`ElementBase.common_oxidation_states`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.common_oxidation_states)


            * [`ElementBase.data`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.data)


            * [`ElementBase.electron_affinity`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.electron_affinity)


            * [`ElementBase.electronic_structure`](pymatgen.core.md#id3)


            * [`ElementBase.from_Z()`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.from_Z)


            * [`ElementBase.from_dict()`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.from_dict)


            * [`ElementBase.from_name()`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.from_name)


            * [`ElementBase.from_row_and_group()`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.from_row_and_group)


            * [`ElementBase.full_electronic_structure`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.full_electronic_structure)


            * [`ElementBase.ground_state_term_symbol`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.ground_state_term_symbol)


            * [`ElementBase.group`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.group)


            * [`ElementBase.icsd_oxidation_states`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.icsd_oxidation_states)


            * [`ElementBase.ionic_radii`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.ionic_radii)


            * [`ElementBase.ionization_energy`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.ionization_energy)


            * [`ElementBase.is_actinoid`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.is_actinoid)


            * [`ElementBase.is_alkali`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.is_alkali)


            * [`ElementBase.is_alkaline`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.is_alkaline)


            * [`ElementBase.is_chalcogen`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.is_chalcogen)


            * [`ElementBase.is_halogen`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.is_halogen)


            * [`ElementBase.is_lanthanoid`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.is_lanthanoid)


            * [`ElementBase.is_metal`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.is_metal)


            * [`ElementBase.is_metalloid`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.is_metalloid)


            * [`ElementBase.is_noble_gas`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.is_noble_gas)


            * [`ElementBase.is_post_transition_metal`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.is_post_transition_metal)


            * [`ElementBase.is_quadrupolar`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.is_quadrupolar)


            * [`ElementBase.is_rare_earth_metal`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.is_rare_earth_metal)


            * [`ElementBase.is_transition_metal`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.is_transition_metal)


            * [`ElementBase.is_valid_symbol()`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.is_valid_symbol)


            * [`ElementBase.iupac_ordering`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.iupac_ordering)


            * [`ElementBase.max_oxidation_state`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.max_oxidation_state)


            * [`ElementBase.min_oxidation_state`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.min_oxidation_state)


            * [`ElementBase.nmr_quadrupole_moment`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.nmr_quadrupole_moment)


            * [`ElementBase.number`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.number)


            * [`ElementBase.oxidation_states`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.oxidation_states)


            * [`ElementBase.print_periodic_table()`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.print_periodic_table)


            * [`ElementBase.row`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.row)


            * [`ElementBase.term_symbols`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.term_symbols)


            * [`ElementBase.valence`](pymatgen.core.md#pymatgen.core.periodic_table.ElementBase.valence)


        * [`Specie`](pymatgen.core.md#pymatgen.core.periodic_table.Specie)


        * [`Species`](pymatgen.core.md#pymatgen.core.periodic_table.Species)


            * [`Species.STRING_MODE`](pymatgen.core.md#pymatgen.core.periodic_table.Species.STRING_MODE)


            * [`Species.as_dict()`](pymatgen.core.md#pymatgen.core.periodic_table.Species.as_dict)


            * [`Species.element`](pymatgen.core.md#pymatgen.core.periodic_table.Species.element)


            * [`Species.from_dict()`](pymatgen.core.md#pymatgen.core.periodic_table.Species.from_dict)


            * [`Species.from_str()`](pymatgen.core.md#pymatgen.core.periodic_table.Species.from_str)


            * [`Species.from_string()`](pymatgen.core.md#pymatgen.core.periodic_table.Species.from_string)


            * [`Species.get_crystal_field_spin()`](pymatgen.core.md#pymatgen.core.periodic_table.Species.get_crystal_field_spin)


            * [`Species.get_nmr_quadrupole_moment()`](pymatgen.core.md#pymatgen.core.periodic_table.Species.get_nmr_quadrupole_moment)


            * [`Species.get_shannon_radius()`](pymatgen.core.md#pymatgen.core.periodic_table.Species.get_shannon_radius)


            * [`Species.ionic_radius`](pymatgen.core.md#pymatgen.core.periodic_table.Species.ionic_radius)


            * [`Species.oxi_state`](pymatgen.core.md#pymatgen.core.periodic_table.Species.oxi_state)


            * [`Species.spin`](pymatgen.core.md#pymatgen.core.periodic_table.Species.spin)


            * [`Species.to_pretty_string()`](pymatgen.core.md#pymatgen.core.periodic_table.Species.to_pretty_string)


        * [`get_el_sp()`](pymatgen.core.md#pymatgen.core.periodic_table.get_el_sp)


    * [pymatgen.core.sites module](pymatgen.core.md#module-pymatgen.core.sites)


        * [`PeriodicSite`](pymatgen.core.md#pymatgen.core.sites.PeriodicSite)


            * [`PeriodicSite._abc_impl`](pymatgen.core.md#pymatgen.core.sites.PeriodicSite._abc_impl)


            * [`PeriodicSite.a`](pymatgen.core.md#pymatgen.core.sites.PeriodicSite.a)


            * [`PeriodicSite.as_dict()`](pymatgen.core.md#pymatgen.core.sites.PeriodicSite.as_dict)


            * [`PeriodicSite.b`](pymatgen.core.md#pymatgen.core.sites.PeriodicSite.b)


            * [`PeriodicSite.c`](pymatgen.core.md#pymatgen.core.sites.PeriodicSite.c)


            * [`PeriodicSite.coords`](pymatgen.core.md#pymatgen.core.sites.PeriodicSite.coords)


            * [`PeriodicSite.distance()`](pymatgen.core.md#pymatgen.core.sites.PeriodicSite.distance)


            * [`PeriodicSite.distance_and_image()`](pymatgen.core.md#pymatgen.core.sites.PeriodicSite.distance_and_image)


            * [`PeriodicSite.distance_and_image_from_frac_coords()`](pymatgen.core.md#pymatgen.core.sites.PeriodicSite.distance_and_image_from_frac_coords)


            * [`PeriodicSite.frac_coords`](pymatgen.core.md#pymatgen.core.sites.PeriodicSite.frac_coords)


            * [`PeriodicSite.from_dict()`](pymatgen.core.md#pymatgen.core.sites.PeriodicSite.from_dict)


            * [`PeriodicSite.is_periodic_image()`](pymatgen.core.md#pymatgen.core.sites.PeriodicSite.is_periodic_image)


            * [`PeriodicSite.lattice`](pymatgen.core.md#pymatgen.core.sites.PeriodicSite.lattice)


            * [`PeriodicSite.to_unit_cell()`](pymatgen.core.md#pymatgen.core.sites.PeriodicSite.to_unit_cell)


            * [`PeriodicSite.x`](pymatgen.core.md#pymatgen.core.sites.PeriodicSite.x)


            * [`PeriodicSite.y`](pymatgen.core.md#pymatgen.core.sites.PeriodicSite.y)


            * [`PeriodicSite.z`](pymatgen.core.md#pymatgen.core.sites.PeriodicSite.z)


        * [`Site`](pymatgen.core.md#pymatgen.core.sites.Site)


            * [`Site._abc_impl`](pymatgen.core.md#pymatgen.core.sites.Site._abc_impl)


            * [`Site.as_dict()`](pymatgen.core.md#pymatgen.core.sites.Site.as_dict)


            * [`Site.distance()`](pymatgen.core.md#pymatgen.core.sites.Site.distance)


            * [`Site.distance_from_point()`](pymatgen.core.md#pymatgen.core.sites.Site.distance_from_point)


            * [`Site.from_dict()`](pymatgen.core.md#pymatgen.core.sites.Site.from_dict)


            * [`Site.is_ordered`](pymatgen.core.md#pymatgen.core.sites.Site.is_ordered)


            * [`Site.label`](pymatgen.core.md#pymatgen.core.sites.Site.label)


            * [`Site.position_atol`](pymatgen.core.md#pymatgen.core.sites.Site.position_atol)


            * [`Site.specie`](pymatgen.core.md#pymatgen.core.sites.Site.specie)


            * [`Site.species`](pymatgen.core.md#pymatgen.core.sites.Site.species)


            * [`Site.species_string`](pymatgen.core.md#pymatgen.core.sites.Site.species_string)


            * [`Site.x`](pymatgen.core.md#pymatgen.core.sites.Site.x)


            * [`Site.y`](pymatgen.core.md#pymatgen.core.sites.Site.y)


            * [`Site.z`](pymatgen.core.md#pymatgen.core.sites.Site.z)


    * [pymatgen.core.spectrum module](pymatgen.core.md#module-pymatgen.core.spectrum)


        * [`Spectrum`](pymatgen.core.md#pymatgen.core.spectrum.Spectrum)


            * [`Spectrum.XLABEL`](pymatgen.core.md#pymatgen.core.spectrum.Spectrum.XLABEL)


            * [`Spectrum.YLABEL`](pymatgen.core.md#pymatgen.core.spectrum.Spectrum.YLABEL)


            * [`Spectrum.copy()`](pymatgen.core.md#pymatgen.core.spectrum.Spectrum.copy)


            * [`Spectrum.get_interpolated_value()`](pymatgen.core.md#pymatgen.core.spectrum.Spectrum.get_interpolated_value)


            * [`Spectrum.normalize()`](pymatgen.core.md#pymatgen.core.spectrum.Spectrum.normalize)


            * [`Spectrum.smear()`](pymatgen.core.md#pymatgen.core.spectrum.Spectrum.smear)


        * [`lorentzian()`](pymatgen.core.md#pymatgen.core.spectrum.lorentzian)


    * [pymatgen.core.structure module](pymatgen.core.md#module-pymatgen.core.structure)


        * [`IMolecule`](pymatgen.core.md#pymatgen.core.structure.IMolecule)


            * [`IMolecule._abc_impl`](pymatgen.core.md#pymatgen.core.structure.IMolecule._abc_impl)


            * [`IMolecule._find_nn_pos_before_site()`](pymatgen.core.md#pymatgen.core.structure.IMolecule._find_nn_pos_before_site)


            * [`IMolecule._properties`](pymatgen.core.md#pymatgen.core.structure.IMolecule._properties)


            * [`IMolecule.as_dict()`](pymatgen.core.md#pymatgen.core.structure.IMolecule.as_dict)


            * [`IMolecule.break_bond()`](pymatgen.core.md#pymatgen.core.structure.IMolecule.break_bond)


            * [`IMolecule.center_of_mass`](pymatgen.core.md#pymatgen.core.structure.IMolecule.center_of_mass)


            * [`IMolecule.charge`](pymatgen.core.md#pymatgen.core.structure.IMolecule.charge)


            * [`IMolecule.copy()`](pymatgen.core.md#pymatgen.core.structure.IMolecule.copy)


            * [`IMolecule.from_dict()`](pymatgen.core.md#pymatgen.core.structure.IMolecule.from_dict)


            * [`IMolecule.from_file()`](pymatgen.core.md#pymatgen.core.structure.IMolecule.from_file)


            * [`IMolecule.from_sites()`](pymatgen.core.md#pymatgen.core.structure.IMolecule.from_sites)


            * [`IMolecule.from_str()`](pymatgen.core.md#pymatgen.core.structure.IMolecule.from_str)


            * [`IMolecule.get_boxed_structure()`](pymatgen.core.md#pymatgen.core.structure.IMolecule.get_boxed_structure)


            * [`IMolecule.get_centered_molecule()`](pymatgen.core.md#pymatgen.core.structure.IMolecule.get_centered_molecule)


            * [`IMolecule.get_covalent_bonds()`](pymatgen.core.md#pymatgen.core.structure.IMolecule.get_covalent_bonds)


            * [`IMolecule.get_distance()`](pymatgen.core.md#pymatgen.core.structure.IMolecule.get_distance)


            * [`IMolecule.get_neighbors()`](pymatgen.core.md#pymatgen.core.structure.IMolecule.get_neighbors)


            * [`IMolecule.get_neighbors_in_shell()`](pymatgen.core.md#pymatgen.core.structure.IMolecule.get_neighbors_in_shell)


            * [`IMolecule.get_sites_in_sphere()`](pymatgen.core.md#pymatgen.core.structure.IMolecule.get_sites_in_sphere)


            * [`IMolecule.get_zmatrix()`](pymatgen.core.md#pymatgen.core.structure.IMolecule.get_zmatrix)


            * [`IMolecule.nelectrons`](pymatgen.core.md#pymatgen.core.structure.IMolecule.nelectrons)


            * [`IMolecule.spin_multiplicity`](pymatgen.core.md#pymatgen.core.structure.IMolecule.spin_multiplicity)


            * [`IMolecule.to()`](pymatgen.core.md#pymatgen.core.structure.IMolecule.to)


        * [`IStructure`](pymatgen.core.md#pymatgen.core.structure.IStructure)


            * [`IStructure._abc_impl`](pymatgen.core.md#pymatgen.core.structure.IStructure._abc_impl)


            * [`IStructure._get_neighbor_list_py()`](pymatgen.core.md#pymatgen.core.structure.IStructure._get_neighbor_list_py)


            * [`IStructure._properties`](pymatgen.core.md#pymatgen.core.structure.IStructure._properties)


            * [`IStructure.as_dataframe()`](pymatgen.core.md#pymatgen.core.structure.IStructure.as_dataframe)


            * [`IStructure.as_dict()`](pymatgen.core.md#pymatgen.core.structure.IStructure.as_dict)


            * [`IStructure.charge`](pymatgen.core.md#pymatgen.core.structure.IStructure.charge)


            * [`IStructure.copy()`](pymatgen.core.md#pymatgen.core.structure.IStructure.copy)


            * [`IStructure.density`](pymatgen.core.md#pymatgen.core.structure.IStructure.density)


            * [`IStructure.distance_matrix`](pymatgen.core.md#pymatgen.core.structure.IStructure.distance_matrix)


            * [`IStructure.frac_coords`](pymatgen.core.md#pymatgen.core.structure.IStructure.frac_coords)


            * [`IStructure.from_dict()`](pymatgen.core.md#pymatgen.core.structure.IStructure.from_dict)


            * [`IStructure.from_file()`](pymatgen.core.md#pymatgen.core.structure.IStructure.from_file)


            * [`IStructure.from_magnetic_spacegroup()`](pymatgen.core.md#pymatgen.core.structure.IStructure.from_magnetic_spacegroup)


            * [`IStructure.from_sites()`](pymatgen.core.md#pymatgen.core.structure.IStructure.from_sites)


            * [`IStructure.from_spacegroup()`](pymatgen.core.md#pymatgen.core.structure.IStructure.from_spacegroup)


            * [`IStructure.from_str()`](pymatgen.core.md#pymatgen.core.structure.IStructure.from_str)


            * [`IStructure.get_all_neighbors()`](pymatgen.core.md#pymatgen.core.structure.IStructure.get_all_neighbors)


            * [`IStructure.get_all_neighbors_old()`](pymatgen.core.md#pymatgen.core.structure.IStructure.get_all_neighbors_old)


            * [`IStructure.get_all_neighbors_py()`](pymatgen.core.md#pymatgen.core.structure.IStructure.get_all_neighbors_py)


            * [`IStructure.get_distance()`](pymatgen.core.md#pymatgen.core.structure.IStructure.get_distance)


            * [`IStructure.get_miller_index_from_site_indexes()`](pymatgen.core.md#pymatgen.core.structure.IStructure.get_miller_index_from_site_indexes)


            * [`IStructure.get_neighbor_list()`](pymatgen.core.md#pymatgen.core.structure.IStructure.get_neighbor_list)


            * [`IStructure.get_neighbors()`](pymatgen.core.md#pymatgen.core.structure.IStructure.get_neighbors)


            * [`IStructure.get_neighbors_in_shell()`](pymatgen.core.md#pymatgen.core.structure.IStructure.get_neighbors_in_shell)


            * [`IStructure.get_neighbors_old()`](pymatgen.core.md#pymatgen.core.structure.IStructure.get_neighbors_old)


            * [`IStructure.get_orderings()`](pymatgen.core.md#pymatgen.core.structure.IStructure.get_orderings)


            * [`IStructure.get_primitive_structure()`](pymatgen.core.md#pymatgen.core.structure.IStructure.get_primitive_structure)


            * [`IStructure.get_reduced_structure()`](pymatgen.core.md#pymatgen.core.structure.IStructure.get_reduced_structure)


            * [`IStructure.get_sites_in_sphere()`](pymatgen.core.md#pymatgen.core.structure.IStructure.get_sites_in_sphere)


            * [`IStructure.get_sorted_structure()`](pymatgen.core.md#pymatgen.core.structure.IStructure.get_sorted_structure)


            * [`IStructure.get_space_group_info()`](pymatgen.core.md#pymatgen.core.structure.IStructure.get_space_group_info)


            * [`IStructure.get_symmetric_neighbor_list()`](pymatgen.core.md#pymatgen.core.structure.IStructure.get_symmetric_neighbor_list)


            * [`IStructure.interpolate()`](pymatgen.core.md#pymatgen.core.structure.IStructure.interpolate)


            * [`IStructure.is_3d_periodic`](pymatgen.core.md#pymatgen.core.structure.IStructure.is_3d_periodic)


            * [`IStructure.lattice`](pymatgen.core.md#pymatgen.core.structure.IStructure.lattice)


            * [`IStructure.matches()`](pymatgen.core.md#pymatgen.core.structure.IStructure.matches)


            * [`IStructure.pbc`](pymatgen.core.md#pymatgen.core.structure.IStructure.pbc)


            * [`IStructure.properties`](pymatgen.core.md#pymatgen.core.structure.IStructure.properties)


            * [`IStructure.to()`](pymatgen.core.md#pymatgen.core.structure.IStructure.to)


            * [`IStructure.unset_charge()`](pymatgen.core.md#pymatgen.core.structure.IStructure.unset_charge)


            * [`IStructure.volume`](pymatgen.core.md#pymatgen.core.structure.IStructure.volume)


        * [`Molecule`](pymatgen.core.md#pymatgen.core.structure.Molecule)


            * [`Molecule._abc_impl`](pymatgen.core.md#pymatgen.core.structure.Molecule._abc_impl)


            * [`Molecule._properties`](pymatgen.core.md#pymatgen.core.structure.Molecule._properties)


            * [`Molecule.append()`](pymatgen.core.md#pymatgen.core.structure.Molecule.append)


            * [`Molecule.apply_operation()`](pymatgen.core.md#pymatgen.core.structure.Molecule.apply_operation)


            * [`Molecule.calculate()`](pymatgen.core.md#pymatgen.core.structure.Molecule.calculate)


            * [`Molecule.insert()`](pymatgen.core.md#pymatgen.core.structure.Molecule.insert)


            * [`Molecule.perturb()`](pymatgen.core.md#pymatgen.core.structure.Molecule.perturb)


            * [`Molecule.relax()`](pymatgen.core.md#pymatgen.core.structure.Molecule.relax)


            * [`Molecule.remove_sites()`](pymatgen.core.md#pymatgen.core.structure.Molecule.remove_sites)


            * [`Molecule.remove_species()`](pymatgen.core.md#pymatgen.core.structure.Molecule.remove_species)


            * [`Molecule.rotate_sites()`](pymatgen.core.md#pymatgen.core.structure.Molecule.rotate_sites)


            * [`Molecule.set_charge_and_spin()`](pymatgen.core.md#pymatgen.core.structure.Molecule.set_charge_and_spin)


            * [`Molecule.substitute()`](pymatgen.core.md#pymatgen.core.structure.Molecule.substitute)


            * [`Molecule.translate_sites()`](pymatgen.core.md#pymatgen.core.structure.Molecule.translate_sites)


        * [`Neighbor`](pymatgen.core.md#pymatgen.core.structure.Neighbor)


            * [`Neighbor._abc_impl`](pymatgen.core.md#pymatgen.core.structure.Neighbor._abc_impl)


            * [`Neighbor._species`](pymatgen.core.md#pymatgen.core.structure.Neighbor._species)


            * [`Neighbor.as_dict()`](pymatgen.core.md#pymatgen.core.structure.Neighbor.as_dict)


            * [`Neighbor.coords`](pymatgen.core.md#pymatgen.core.structure.Neighbor.coords)


            * [`Neighbor.from_dict()`](pymatgen.core.md#pymatgen.core.structure.Neighbor.from_dict)


            * [`Neighbor.properties`](pymatgen.core.md#pymatgen.core.structure.Neighbor.properties)


        * [`PeriodicNeighbor`](pymatgen.core.md#pymatgen.core.structure.PeriodicNeighbor)


            * [`PeriodicNeighbor._abc_impl`](pymatgen.core.md#pymatgen.core.structure.PeriodicNeighbor._abc_impl)


            * [`PeriodicNeighbor._coords`](pymatgen.core.md#pymatgen.core.structure.PeriodicNeighbor._coords)


            * [`PeriodicNeighbor._frac_coords`](pymatgen.core.md#pymatgen.core.structure.PeriodicNeighbor._frac_coords)


            * [`PeriodicNeighbor._lattice`](pymatgen.core.md#pymatgen.core.structure.PeriodicNeighbor._lattice)


            * [`PeriodicNeighbor._species`](pymatgen.core.md#pymatgen.core.structure.PeriodicNeighbor._species)


            * [`PeriodicNeighbor.as_dict()`](pymatgen.core.md#pymatgen.core.structure.PeriodicNeighbor.as_dict)


            * [`PeriodicNeighbor.coords`](pymatgen.core.md#pymatgen.core.structure.PeriodicNeighbor.coords)


            * [`PeriodicNeighbor.from_dict()`](pymatgen.core.md#pymatgen.core.structure.PeriodicNeighbor.from_dict)


            * [`PeriodicNeighbor.properties`](pymatgen.core.md#pymatgen.core.structure.PeriodicNeighbor.properties)


        * [`SiteCollection`](pymatgen.core.md#pymatgen.core.structure.SiteCollection)


            * [`SiteCollection.DISTANCE_TOLERANCE`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.DISTANCE_TOLERANCE)


            * [`SiteCollection._abc_impl`](pymatgen.core.md#pymatgen.core.structure.SiteCollection._abc_impl)


            * [`SiteCollection._calculate()`](pymatgen.core.md#pymatgen.core.structure.SiteCollection._calculate)


            * [`SiteCollection._prep_calculator()`](pymatgen.core.md#pymatgen.core.structure.SiteCollection._prep_calculator)


            * [`SiteCollection._properties`](pymatgen.core.md#pymatgen.core.structure.SiteCollection._properties)


            * [`SiteCollection._relax()`](pymatgen.core.md#pymatgen.core.structure.SiteCollection._relax)


            * [`SiteCollection.add_oxidation_state_by_element()`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.add_oxidation_state_by_element)


            * [`SiteCollection.add_oxidation_state_by_guess()`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.add_oxidation_state_by_guess)


            * [`SiteCollection.add_oxidation_state_by_site()`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.add_oxidation_state_by_site)


            * [`SiteCollection.add_site_property()`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.add_site_property)


            * [`SiteCollection.add_spin_by_element()`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.add_spin_by_element)


            * [`SiteCollection.add_spin_by_site()`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.add_spin_by_site)


            * [`SiteCollection.atomic_numbers`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.atomic_numbers)


            * [`SiteCollection.cart_coords`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.cart_coords)


            * [`SiteCollection.charge`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.charge)


            * [`SiteCollection.composition`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.composition)


            * [`SiteCollection.copy()`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.copy)


            * [`SiteCollection.distance_matrix`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.distance_matrix)


            * [`SiteCollection.elements`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.elements)


            * [`SiteCollection.extract_cluster()`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.extract_cluster)


            * [`SiteCollection.formula`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.formula)


            * [`SiteCollection.from_file()`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.from_file)


            * [`SiteCollection.from_str()`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.from_str)


            * [`SiteCollection.get_angle()`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.get_angle)


            * [`SiteCollection.get_dihedral()`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.get_dihedral)


            * [`SiteCollection.get_distance()`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.get_distance)


            * [`SiteCollection.group_by_types()`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.group_by_types)


            * [`SiteCollection.indices_from_symbol()`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.indices_from_symbol)


            * [`SiteCollection.is_ordered`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.is_ordered)


            * [`SiteCollection.is_valid()`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.is_valid)


            * [`SiteCollection.labels`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.labels)


            * [`SiteCollection.ntypesp`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.ntypesp)


            * [`SiteCollection.num_sites`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.num_sites)


            * [`SiteCollection.remove_oxidation_states()`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.remove_oxidation_states)


            * [`SiteCollection.remove_site_property()`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.remove_site_property)


            * [`SiteCollection.remove_spin()`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.remove_spin)


            * [`SiteCollection.replace_species()`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.replace_species)


            * [`SiteCollection.site_properties`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.site_properties)


            * [`SiteCollection.sites`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.sites)


            * [`SiteCollection.species`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.species)


            * [`SiteCollection.species_and_occu`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.species_and_occu)


            * [`SiteCollection.symbol_set`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.symbol_set)


            * [`SiteCollection.to()`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.to)


            * [`SiteCollection.types_of_specie`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.types_of_specie)


            * [`SiteCollection.types_of_species`](pymatgen.core.md#pymatgen.core.structure.SiteCollection.types_of_species)


        * [`Structure`](pymatgen.core.md#pymatgen.core.structure.Structure)


            * [`Structure._abc_impl`](pymatgen.core.md#pymatgen.core.structure.Structure._abc_impl)


            * [`Structure._properties`](pymatgen.core.md#pymatgen.core.structure.Structure._properties)


            * [`Structure._sites`](pymatgen.core.md#pymatgen.core.structure.Structure._sites)


            * [`Structure.append()`](pymatgen.core.md#pymatgen.core.structure.Structure.append)


            * [`Structure.apply_operation()`](pymatgen.core.md#pymatgen.core.structure.Structure.apply_operation)


            * [`Structure.apply_strain()`](pymatgen.core.md#pymatgen.core.structure.Structure.apply_strain)


            * [`Structure.calculate()`](pymatgen.core.md#pymatgen.core.structure.Structure.calculate)


            * [`Structure.from_prototype()`](pymatgen.core.md#pymatgen.core.structure.Structure.from_prototype)


            * [`Structure.insert()`](pymatgen.core.md#pymatgen.core.structure.Structure.insert)


            * [`Structure.lattice`](pymatgen.core.md#pymatgen.core.structure.Structure.lattice)


            * [`Structure.make_supercell()`](pymatgen.core.md#pymatgen.core.structure.Structure.make_supercell)


            * [`Structure.merge_sites()`](pymatgen.core.md#pymatgen.core.structure.Structure.merge_sites)


            * [`Structure.perturb()`](pymatgen.core.md#pymatgen.core.structure.Structure.perturb)


            * [`Structure.relax()`](pymatgen.core.md#pymatgen.core.structure.Structure.relax)


            * [`Structure.remove_sites()`](pymatgen.core.md#pymatgen.core.structure.Structure.remove_sites)


            * [`Structure.remove_species()`](pymatgen.core.md#pymatgen.core.structure.Structure.remove_species)


            * [`Structure.replace()`](pymatgen.core.md#pymatgen.core.structure.Structure.replace)


            * [`Structure.rotate_sites()`](pymatgen.core.md#pymatgen.core.structure.Structure.rotate_sites)


            * [`Structure.scale_lattice()`](pymatgen.core.md#pymatgen.core.structure.Structure.scale_lattice)


            * [`Structure.set_charge()`](pymatgen.core.md#pymatgen.core.structure.Structure.set_charge)


            * [`Structure.sort()`](pymatgen.core.md#pymatgen.core.structure.Structure.sort)


            * [`Structure.substitute()`](pymatgen.core.md#pymatgen.core.structure.Structure.substitute)


            * [`Structure.translate_sites()`](pymatgen.core.md#pymatgen.core.structure.Structure.translate_sites)


        * [`StructureError`](pymatgen.core.md#pymatgen.core.structure.StructureError)


    * [pymatgen.core.surface module](pymatgen.core.md#module-pymatgen.core.surface)


        * [`ReconstructionGenerator`](pymatgen.core.md#pymatgen.core.surface.ReconstructionGenerator)


            * [`ReconstructionGenerator.slabgen_params`](pymatgen.core.md#pymatgen.core.surface.ReconstructionGenerator.slabgen_params)


            * [`ReconstructionGenerator.trans_matrix`](pymatgen.core.md#pymatgen.core.surface.ReconstructionGenerator.trans_matrix)


            * [`ReconstructionGenerator.reconstruction_json`](pymatgen.core.md#pymatgen.core.surface.ReconstructionGenerator.reconstruction_json)


            * [`ReconstructionGenerator.termination`](pymatgen.core.md#pymatgen.core.surface.ReconstructionGenerator.termination)


            * [`ReconstructionGenerator.build_slabs()`](pymatgen.core.md#pymatgen.core.surface.ReconstructionGenerator.build_slabs)


            * [`ReconstructionGenerator.get_unreconstructed_slabs()`](pymatgen.core.md#pymatgen.core.surface.ReconstructionGenerator.get_unreconstructed_slabs)


        * [`Slab`](pymatgen.core.md#pymatgen.core.surface.Slab)


            * [`Slab.miller_index`](pymatgen.core.md#pymatgen.core.surface.Slab.miller_index)


            * [`Slab.scale_factor`](pymatgen.core.md#pymatgen.core.surface.Slab.scale_factor)


            * [`Slab.shift`](pymatgen.core.md#pymatgen.core.surface.Slab.shift)


            * [`Slab._abc_impl`](pymatgen.core.md#pymatgen.core.surface.Slab._abc_impl)


            * [`Slab._properties`](pymatgen.core.md#pymatgen.core.surface.Slab._properties)


            * [`Slab._sites`](pymatgen.core.md#pymatgen.core.surface.Slab._sites)


            * [`Slab.add_adsorbate_atom()`](pymatgen.core.md#pymatgen.core.surface.Slab.add_adsorbate_atom)


            * [`Slab.as_dict()`](pymatgen.core.md#pymatgen.core.surface.Slab.as_dict)


            * [`Slab.center_of_mass`](pymatgen.core.md#pymatgen.core.surface.Slab.center_of_mass)


            * [`Slab.copy()`](pymatgen.core.md#pymatgen.core.surface.Slab.copy)


            * [`Slab.dipole`](pymatgen.core.md#pymatgen.core.surface.Slab.dipole)


            * [`Slab.from_dict()`](pymatgen.core.md#pymatgen.core.surface.Slab.from_dict)


            * [`Slab.get_orthogonal_c_slab()`](pymatgen.core.md#pymatgen.core.surface.Slab.get_orthogonal_c_slab)


            * [`Slab.get_sorted_structure()`](pymatgen.core.md#pymatgen.core.surface.Slab.get_sorted_structure)


            * [`Slab.get_surface_sites()`](pymatgen.core.md#pymatgen.core.surface.Slab.get_surface_sites)


            * [`Slab.get_symmetric_site()`](pymatgen.core.md#pymatgen.core.surface.Slab.get_symmetric_site)


            * [`Slab.get_tasker2_slabs()`](pymatgen.core.md#pymatgen.core.surface.Slab.get_tasker2_slabs)


            * [`Slab.is_polar()`](pymatgen.core.md#pymatgen.core.surface.Slab.is_polar)


            * [`Slab.is_symmetric()`](pymatgen.core.md#pymatgen.core.surface.Slab.is_symmetric)


            * [`Slab.normal`](pymatgen.core.md#pymatgen.core.surface.Slab.normal)


            * [`Slab.surface_area`](pymatgen.core.md#pymatgen.core.surface.Slab.surface_area)


            * [`Slab.symmetrically_add_atom()`](pymatgen.core.md#pymatgen.core.surface.Slab.symmetrically_add_atom)


            * [`Slab.symmetrically_remove_atoms()`](pymatgen.core.md#pymatgen.core.surface.Slab.symmetrically_remove_atoms)


        * [`SlabGenerator`](pymatgen.core.md#pymatgen.core.surface.SlabGenerator)


            * [`SlabGenerator.oriented_unit_cell`](pymatgen.core.md#pymatgen.core.surface.SlabGenerator.oriented_unit_cell)


            * [`SlabGenerator.parent`](pymatgen.core.md#pymatgen.core.surface.SlabGenerator.parent)


            * [`SlabGenerator.lll_reduce`](pymatgen.core.md#pymatgen.core.surface.SlabGenerator.lll_reduce)


            * [`SlabGenerator.center_slab`](pymatgen.core.md#pymatgen.core.surface.SlabGenerator.center_slab)


            * [`SlabGenerator.slab_scale_factor`](pymatgen.core.md#pymatgen.core.surface.SlabGenerator.slab_scale_factor)


            * [`SlabGenerator.miller_index`](pymatgen.core.md#pymatgen.core.surface.SlabGenerator.miller_index)


            * [`SlabGenerator.min_slab_size`](pymatgen.core.md#pymatgen.core.surface.SlabGenerator.min_slab_size)


            * [`SlabGenerator.min_vac_size`](pymatgen.core.md#pymatgen.core.surface.SlabGenerator.min_vac_size)


            * [`SlabGenerator._calculate_possible_shifts()`](pymatgen.core.md#pymatgen.core.surface.SlabGenerator._calculate_possible_shifts)


            * [`SlabGenerator._get_c_ranges()`](pymatgen.core.md#pymatgen.core.surface.SlabGenerator._get_c_ranges)


            * [`SlabGenerator.get_slab()`](pymatgen.core.md#pymatgen.core.surface.SlabGenerator.get_slab)


            * [`SlabGenerator.get_slabs()`](pymatgen.core.md#pymatgen.core.surface.SlabGenerator.get_slabs)


            * [`SlabGenerator.move_to_other_side()`](pymatgen.core.md#pymatgen.core.surface.SlabGenerator.move_to_other_side)


            * [`SlabGenerator.nonstoichiometric_symmetrized_slab()`](pymatgen.core.md#pymatgen.core.surface.SlabGenerator.nonstoichiometric_symmetrized_slab)


            * [`SlabGenerator.repair_broken_bonds()`](pymatgen.core.md#pymatgen.core.surface.SlabGenerator.repair_broken_bonds)


        * [`_reduce_vector()`](pymatgen.core.md#pymatgen.core.surface._reduce_vector)


        * [`center_slab()`](pymatgen.core.md#pymatgen.core.surface.center_slab)


        * [`generate_all_slabs()`](pymatgen.core.md#pymatgen.core.surface.generate_all_slabs)


        * [`get_d()`](pymatgen.core.md#pymatgen.core.surface.get_d)


        * [`get_slab_regions()`](pymatgen.core.md#pymatgen.core.surface.get_slab_regions)


        * [`get_symmetrically_distinct_miller_indices()`](pymatgen.core.md#pymatgen.core.surface.get_symmetrically_distinct_miller_indices)


        * [`get_symmetrically_equivalent_miller_indices()`](pymatgen.core.md#pymatgen.core.surface.get_symmetrically_equivalent_miller_indices)


        * [`hkl_transformation()`](pymatgen.core.md#pymatgen.core.surface.hkl_transformation)


        * [`is_already_analyzed()`](pymatgen.core.md#pymatgen.core.surface.is_already_analyzed)


        * [`miller_index_from_sites()`](pymatgen.core.md#pymatgen.core.surface.miller_index_from_sites)


    * [pymatgen.core.tensors module](pymatgen.core.md#module-pymatgen.core.tensors)


        * [`SquareTensor`](pymatgen.core.md#pymatgen.core.tensors.SquareTensor)


            * [`SquareTensor.det`](pymatgen.core.md#pymatgen.core.tensors.SquareTensor.det)


            * [`SquareTensor.get_scaled()`](pymatgen.core.md#pymatgen.core.tensors.SquareTensor.get_scaled)


            * [`SquareTensor.inv`](pymatgen.core.md#pymatgen.core.tensors.SquareTensor.inv)


            * [`SquareTensor.is_rotation()`](pymatgen.core.md#pymatgen.core.tensors.SquareTensor.is_rotation)


            * [`SquareTensor.polar_decomposition()`](pymatgen.core.md#pymatgen.core.tensors.SquareTensor.polar_decomposition)


            * [`SquareTensor.principal_invariants`](pymatgen.core.md#pymatgen.core.tensors.SquareTensor.principal_invariants)


            * [`SquareTensor.refine_rotation()`](pymatgen.core.md#pymatgen.core.tensors.SquareTensor.refine_rotation)


            * [`SquareTensor.trans`](pymatgen.core.md#pymatgen.core.tensors.SquareTensor.trans)


        * [`Tensor`](pymatgen.core.md#pymatgen.core.tensors.Tensor)


            * [`Tensor.as_dict()`](pymatgen.core.md#pymatgen.core.tensors.Tensor.as_dict)


            * [`Tensor.average_over_unit_sphere()`](pymatgen.core.md#pymatgen.core.tensors.Tensor.average_over_unit_sphere)


            * [`Tensor.convert_to_ieee()`](pymatgen.core.md#pymatgen.core.tensors.Tensor.convert_to_ieee)


            * [`Tensor.einsum_sequence()`](pymatgen.core.md#pymatgen.core.tensors.Tensor.einsum_sequence)


            * [`Tensor.fit_to_structure()`](pymatgen.core.md#pymatgen.core.tensors.Tensor.fit_to_structure)


            * [`Tensor.from_dict()`](pymatgen.core.md#pymatgen.core.tensors.Tensor.from_dict)


            * [`Tensor.from_values_indices()`](pymatgen.core.md#pymatgen.core.tensors.Tensor.from_values_indices)


            * [`Tensor.from_voigt()`](pymatgen.core.md#pymatgen.core.tensors.Tensor.from_voigt)


            * [`Tensor.get_grouped_indices()`](pymatgen.core.md#pymatgen.core.tensors.Tensor.get_grouped_indices)


            * [`Tensor.get_ieee_rotation()`](pymatgen.core.md#pymatgen.core.tensors.Tensor.get_ieee_rotation)


            * [`Tensor.get_symbol_dict()`](pymatgen.core.md#pymatgen.core.tensors.Tensor.get_symbol_dict)


            * [`Tensor.get_voigt_dict()`](pymatgen.core.md#pymatgen.core.tensors.Tensor.get_voigt_dict)


            * [`Tensor.is_fit_to_structure()`](pymatgen.core.md#pymatgen.core.tensors.Tensor.is_fit_to_structure)


            * [`Tensor.is_symmetric()`](pymatgen.core.md#pymatgen.core.tensors.Tensor.is_symmetric)


            * [`Tensor.is_voigt_symmetric()`](pymatgen.core.md#pymatgen.core.tensors.Tensor.is_voigt_symmetric)


            * [`Tensor.populate()`](pymatgen.core.md#pymatgen.core.tensors.Tensor.populate)


            * [`Tensor.project()`](pymatgen.core.md#pymatgen.core.tensors.Tensor.project)


            * [`Tensor.rotate()`](pymatgen.core.md#pymatgen.core.tensors.Tensor.rotate)


            * [`Tensor.round()`](pymatgen.core.md#pymatgen.core.tensors.Tensor.round)


            * [`Tensor.structure_transform()`](pymatgen.core.md#pymatgen.core.tensors.Tensor.structure_transform)


            * [`Tensor.symbol`](pymatgen.core.md#pymatgen.core.tensors.Tensor.symbol)


            * [`Tensor.symmetrized`](pymatgen.core.md#pymatgen.core.tensors.Tensor.symmetrized)


            * [`Tensor.transform()`](pymatgen.core.md#pymatgen.core.tensors.Tensor.transform)


            * [`Tensor.voigt`](pymatgen.core.md#pymatgen.core.tensors.Tensor.voigt)


            * [`Tensor.voigt_symmetrized`](pymatgen.core.md#pymatgen.core.tensors.Tensor.voigt_symmetrized)


            * [`Tensor.zeroed()`](pymatgen.core.md#pymatgen.core.tensors.Tensor.zeroed)


        * [`TensorCollection`](pymatgen.core.md#pymatgen.core.tensors.TensorCollection)


            * [`TensorCollection._abc_impl`](pymatgen.core.md#pymatgen.core.tensors.TensorCollection._abc_impl)


            * [`TensorCollection.as_dict()`](pymatgen.core.md#pymatgen.core.tensors.TensorCollection.as_dict)


            * [`TensorCollection.convert_to_ieee()`](pymatgen.core.md#pymatgen.core.tensors.TensorCollection.convert_to_ieee)


            * [`TensorCollection.fit_to_structure()`](pymatgen.core.md#pymatgen.core.tensors.TensorCollection.fit_to_structure)


            * [`TensorCollection.from_dict()`](pymatgen.core.md#pymatgen.core.tensors.TensorCollection.from_dict)


            * [`TensorCollection.from_voigt()`](pymatgen.core.md#pymatgen.core.tensors.TensorCollection.from_voigt)


            * [`TensorCollection.is_fit_to_structure()`](pymatgen.core.md#pymatgen.core.tensors.TensorCollection.is_fit_to_structure)


            * [`TensorCollection.is_symmetric()`](pymatgen.core.md#pymatgen.core.tensors.TensorCollection.is_symmetric)


            * [`TensorCollection.is_voigt_symmetric()`](pymatgen.core.md#pymatgen.core.tensors.TensorCollection.is_voigt_symmetric)


            * [`TensorCollection.ranks`](pymatgen.core.md#pymatgen.core.tensors.TensorCollection.ranks)


            * [`TensorCollection.rotate()`](pymatgen.core.md#pymatgen.core.tensors.TensorCollection.rotate)


            * [`TensorCollection.round()`](pymatgen.core.md#pymatgen.core.tensors.TensorCollection.round)


            * [`TensorCollection.symmetrized`](pymatgen.core.md#pymatgen.core.tensors.TensorCollection.symmetrized)


            * [`TensorCollection.transform()`](pymatgen.core.md#pymatgen.core.tensors.TensorCollection.transform)


            * [`TensorCollection.voigt`](pymatgen.core.md#pymatgen.core.tensors.TensorCollection.voigt)


            * [`TensorCollection.voigt_symmetrized`](pymatgen.core.md#pymatgen.core.tensors.TensorCollection.voigt_symmetrized)


            * [`TensorCollection.zeroed()`](pymatgen.core.md#pymatgen.core.tensors.TensorCollection.zeroed)


        * [`TensorMapping`](pymatgen.core.md#pymatgen.core.tensors.TensorMapping)


            * [`TensorMapping._abc_impl`](pymatgen.core.md#pymatgen.core.tensors.TensorMapping._abc_impl)


            * [`TensorMapping._get_item_index()`](pymatgen.core.md#pymatgen.core.tensors.TensorMapping._get_item_index)


            * [`TensorMapping.items()`](pymatgen.core.md#pymatgen.core.tensors.TensorMapping.items)


            * [`TensorMapping.values()`](pymatgen.core.md#pymatgen.core.tensors.TensorMapping.values)


        * [`get_uvec()`](pymatgen.core.md#pymatgen.core.tensors.get_uvec)


        * [`symmetry_reduce()`](pymatgen.core.md#pymatgen.core.tensors.symmetry_reduce)


    * [pymatgen.core.trajectory module](pymatgen.core.md#module-pymatgen.core.trajectory)


        * [`Trajectory`](pymatgen.core.md#pymatgen.core.trajectory.Trajectory)


            * [`Trajectory._check_frame_props()`](pymatgen.core.md#pymatgen.core.trajectory.Trajectory._check_frame_props)


            * [`Trajectory._check_site_props()`](pymatgen.core.md#pymatgen.core.trajectory.Trajectory._check_site_props)


            * [`Trajectory._combine_frame_props()`](pymatgen.core.md#pymatgen.core.trajectory.Trajectory._combine_frame_props)


            * [`Trajectory._combine_lattice()`](pymatgen.core.md#pymatgen.core.trajectory.Trajectory._combine_lattice)


            * [`Trajectory._combine_site_props()`](pymatgen.core.md#pymatgen.core.trajectory.Trajectory._combine_site_props)


            * [`Trajectory._get_site_props()`](pymatgen.core.md#pymatgen.core.trajectory.Trajectory._get_site_props)


            * [`Trajectory.as_dict()`](pymatgen.core.md#pymatgen.core.trajectory.Trajectory.as_dict)


            * [`Trajectory.extend()`](pymatgen.core.md#pymatgen.core.trajectory.Trajectory.extend)


            * [`Trajectory.from_file()`](pymatgen.core.md#pymatgen.core.trajectory.Trajectory.from_file)


            * [`Trajectory.from_molecules()`](pymatgen.core.md#pymatgen.core.trajectory.Trajectory.from_molecules)


            * [`Trajectory.from_structures()`](pymatgen.core.md#pymatgen.core.trajectory.Trajectory.from_structures)


            * [`Trajectory.get_molecule()`](pymatgen.core.md#pymatgen.core.trajectory.Trajectory.get_molecule)


            * [`Trajectory.get_structure()`](pymatgen.core.md#pymatgen.core.trajectory.Trajectory.get_structure)


            * [`Trajectory.to_displacements()`](pymatgen.core.md#pymatgen.core.trajectory.Trajectory.to_displacements)


            * [`Trajectory.to_positions()`](pymatgen.core.md#pymatgen.core.trajectory.Trajectory.to_positions)


            * [`Trajectory.write_Xdatcar()`](pymatgen.core.md#pymatgen.core.trajectory.Trajectory.write_Xdatcar)


    * [pymatgen.core.units module](pymatgen.core.md#module-pymatgen.core.units)


        * [`ArrayWithUnit`](pymatgen.core.md#pymatgen.core.units.ArrayWithUnit)


            * [`ArrayWithUnit.Error`](pymatgen.core.md#pymatgen.core.units.ArrayWithUnit.Error)


            * [`ArrayWithUnit.as_base_units`](pymatgen.core.md#pymatgen.core.units.ArrayWithUnit.as_base_units)


            * [`ArrayWithUnit.conversions()`](pymatgen.core.md#pymatgen.core.units.ArrayWithUnit.conversions)


            * [`ArrayWithUnit.supported_units`](pymatgen.core.md#pymatgen.core.units.ArrayWithUnit.supported_units)


            * [`ArrayWithUnit.to()`](pymatgen.core.md#pymatgen.core.units.ArrayWithUnit.to)


            * [`ArrayWithUnit.unit`](pymatgen.core.md#pymatgen.core.units.ArrayWithUnit.unit)


            * [`ArrayWithUnit.unit_type`](pymatgen.core.md#pymatgen.core.units.ArrayWithUnit.unit_type)


        * [`Charge`](pymatgen.core.md#pymatgen.core.units.Charge)


        * [`Energy`](pymatgen.core.md#pymatgen.core.units.Energy)


        * [`FloatWithUnit`](pymatgen.core.md#pymatgen.core.units.FloatWithUnit)


            * [`FloatWithUnit.Error`](pymatgen.core.md#pymatgen.core.units.FloatWithUnit.Error)


            * [`FloatWithUnit.as_base_units`](pymatgen.core.md#pymatgen.core.units.FloatWithUnit.as_base_units)


            * [`FloatWithUnit.from_str()`](pymatgen.core.md#pymatgen.core.units.FloatWithUnit.from_str)


            * [`FloatWithUnit.from_string()`](pymatgen.core.md#pymatgen.core.units.FloatWithUnit.from_string)


            * [`FloatWithUnit.supported_units`](pymatgen.core.md#pymatgen.core.units.FloatWithUnit.supported_units)


            * [`FloatWithUnit.to()`](pymatgen.core.md#pymatgen.core.units.FloatWithUnit.to)


            * [`FloatWithUnit.unit`](pymatgen.core.md#pymatgen.core.units.FloatWithUnit.unit)


            * [`FloatWithUnit.unit_type`](pymatgen.core.md#pymatgen.core.units.FloatWithUnit.unit_type)


        * [`Length`](pymatgen.core.md#pymatgen.core.units.Length)


        * [`Mass`](pymatgen.core.md#pymatgen.core.units.Mass)


        * [`Memory`](pymatgen.core.md#pymatgen.core.units.Memory)


        * [`Temp`](pymatgen.core.md#pymatgen.core.units.Temp)


        * [`Time`](pymatgen.core.md#pymatgen.core.units.Time)


        * [`Unit`](pymatgen.core.md#pymatgen.core.units.Unit)


            * [`Unit.Error`](pymatgen.core.md#pymatgen.core.units.Unit.Error)


            * [`Unit._abc_impl`](pymatgen.core.md#pymatgen.core.units.Unit._abc_impl)


            * [`Unit.as_base_units`](pymatgen.core.md#pymatgen.core.units.Unit.as_base_units)


            * [`Unit.get_conversion_factor()`](pymatgen.core.md#pymatgen.core.units.Unit.get_conversion_factor)


        * [`UnitError`](pymatgen.core.md#pymatgen.core.units.UnitError)


        * [`_check_mappings()`](pymatgen.core.md#pymatgen.core.units._check_mappings)


        * [`_get_si_unit()`](pymatgen.core.md#pymatgen.core.units._get_si_unit)


        * [`_my_partial()`](pymatgen.core.md#pymatgen.core.units._my_partial)


        * [`kb`](pymatgen.core.md#pymatgen.core.units.kb)


        * [`obj_with_unit()`](pymatgen.core.md#pymatgen.core.units.obj_with_unit)


        * [`unitized()`](pymatgen.core.md#pymatgen.core.units.unitized)


    * [pymatgen.core.xcfunc module](pymatgen.core.md#module-pymatgen.core.xcfunc)


        * [`XcFunc`](pymatgen.core.md#pymatgen.core.xcfunc.XcFunc)


            * [`XcFunc.abinitixc_to_libxc`](pymatgen.core.md#pymatgen.core.xcfunc.XcFunc.abinitixc_to_libxc)


            * [`XcFunc.aliases()`](pymatgen.core.md#pymatgen.core.xcfunc.XcFunc.aliases)


            * [`XcFunc.as_dict()`](pymatgen.core.md#pymatgen.core.xcfunc.XcFunc.as_dict)


            * [`XcFunc.asxc()`](pymatgen.core.md#pymatgen.core.xcfunc.XcFunc.asxc)


            * [`XcFunc.defined_aliases`](pymatgen.core.md#pymatgen.core.xcfunc.XcFunc.defined_aliases)


            * [`XcFunc.from_abinit_ixc()`](pymatgen.core.md#pymatgen.core.xcfunc.XcFunc.from_abinit_ixc)


            * [`XcFunc.from_dict()`](pymatgen.core.md#pymatgen.core.xcfunc.XcFunc.from_dict)


            * [`XcFunc.from_name()`](pymatgen.core.md#pymatgen.core.xcfunc.XcFunc.from_name)


            * [`XcFunc.from_type_name()`](pymatgen.core.md#pymatgen.core.xcfunc.XcFunc.from_type_name)


            * [`XcFunc.name()`](pymatgen.core.md#pymatgen.core.xcfunc.XcFunc.name)


            * [`XcFunc.type()`](pymatgen.core.md#pymatgen.core.xcfunc.XcFunc.type)


* [pymatgen.electronic_structure package](pymatgen.electronic_structure.md)




    * [pymatgen.electronic_structure.bandstructure module](pymatgen.electronic_structure.md#module-pymatgen.electronic_structure.bandstructure)


        * [`BandStructure`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.BandStructure)


            * [`BandStructure.kpoints`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.BandStructure.kpoints)


            * [`BandStructure.lattice_rec`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.BandStructure.lattice_rec)


            * [`BandStructure.efermi`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.BandStructure.efermi)


            * [`BandStructure.is_spin_polarized`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.BandStructure.is_spin_polarized)


            * [`BandStructure.bands`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.BandStructure.bands)


            * [`BandStructure.nb_bands`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.BandStructure.nb_bands)


            * [`BandStructure.structure`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.BandStructure.structure)


            * [`BandStructure.projections`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.BandStructure.projections)


            * [`BandStructure.as_dict()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.BandStructure.as_dict)


            * [`BandStructure.from_dict()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.BandStructure.from_dict)


            * [`BandStructure.from_old_dict()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.BandStructure.from_old_dict)


            * [`BandStructure.get_band_gap()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.BandStructure.get_band_gap)


            * [`BandStructure.get_cbm()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.BandStructure.get_cbm)


            * [`BandStructure.get_direct_band_gap()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.BandStructure.get_direct_band_gap)


            * [`BandStructure.get_direct_band_gap_dict()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.BandStructure.get_direct_band_gap_dict)


            * [`BandStructure.get_kpoint_degeneracy()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.BandStructure.get_kpoint_degeneracy)


            * [`BandStructure.get_projection_on_elements()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.BandStructure.get_projection_on_elements)


            * [`BandStructure.get_projections_on_elements_and_orbitals()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.BandStructure.get_projections_on_elements_and_orbitals)


            * [`BandStructure.get_sym_eq_kpoints()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.BandStructure.get_sym_eq_kpoints)


            * [`BandStructure.get_vbm()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.BandStructure.get_vbm)


            * [`BandStructure.is_metal()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.BandStructure.is_metal)


        * [`BandStructureSymmLine`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.BandStructureSymmLine)


            * [`BandStructureSymmLine.apply_scissor()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.BandStructureSymmLine.apply_scissor)


            * [`BandStructureSymmLine.as_dict()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.BandStructureSymmLine.as_dict)


            * [`BandStructureSymmLine.get_branch()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.BandStructureSymmLine.get_branch)


            * [`BandStructureSymmLine.get_equivalent_kpoints()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.BandStructureSymmLine.get_equivalent_kpoints)


        * [`Kpoint`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.Kpoint)


            * [`Kpoint.a`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.Kpoint.a)


            * [`Kpoint.as_dict()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.Kpoint.as_dict)


            * [`Kpoint.b`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.Kpoint.b)


            * [`Kpoint.c`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.Kpoint.c)


            * [`Kpoint.cart_coords`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.Kpoint.cart_coords)


            * [`Kpoint.frac_coords`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.Kpoint.frac_coords)


            * [`Kpoint.from_dict()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.Kpoint.from_dict)


            * [`Kpoint.label`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.Kpoint.label)


            * [`Kpoint.lattice`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.Kpoint.lattice)


        * [`LobsterBandStructureSymmLine`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.LobsterBandStructureSymmLine)


            * [`LobsterBandStructureSymmLine.as_dict()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.LobsterBandStructureSymmLine.as_dict)


            * [`LobsterBandStructureSymmLine.from_dict()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.LobsterBandStructureSymmLine.from_dict)


            * [`LobsterBandStructureSymmLine.from_old_dict()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.LobsterBandStructureSymmLine.from_old_dict)


            * [`LobsterBandStructureSymmLine.get_projection_on_elements()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.LobsterBandStructureSymmLine.get_projection_on_elements)


            * [`LobsterBandStructureSymmLine.get_projections_on_elements_and_orbitals()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.LobsterBandStructureSymmLine.get_projections_on_elements_and_orbitals)


        * [`get_reconstructed_band_structure()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.bandstructure.get_reconstructed_band_structure)


    * [pymatgen.electronic_structure.boltztrap module](pymatgen.electronic_structure.md#module-pymatgen.electronic_structure.boltztrap)


        * [`BoltztrapAnalyzer`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapAnalyzer)


            * [`BoltztrapAnalyzer._format_to_output()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapAnalyzer._format_to_output)


            * [`BoltztrapAnalyzer.as_dict()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapAnalyzer.as_dict)


            * [`BoltztrapAnalyzer.check_acc_bzt_bands()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapAnalyzer.check_acc_bzt_bands)


            * [`BoltztrapAnalyzer.from_dict()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapAnalyzer.from_dict)


            * [`BoltztrapAnalyzer.from_files()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapAnalyzer.from_files)


            * [`BoltztrapAnalyzer.get_average_eff_mass()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapAnalyzer.get_average_eff_mass)


            * [`BoltztrapAnalyzer.get_carrier_concentration()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapAnalyzer.get_carrier_concentration)


            * [`BoltztrapAnalyzer.get_complete_dos()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapAnalyzer.get_complete_dos)


            * [`BoltztrapAnalyzer.get_complexity_factor()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapAnalyzer.get_complexity_factor)


            * [`BoltztrapAnalyzer.get_conductivity()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapAnalyzer.get_conductivity)


            * [`BoltztrapAnalyzer.get_extreme()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapAnalyzer.get_extreme)


            * [`BoltztrapAnalyzer.get_hall_carrier_concentration()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapAnalyzer.get_hall_carrier_concentration)


            * [`BoltztrapAnalyzer.get_mu_bounds()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapAnalyzer.get_mu_bounds)


            * [`BoltztrapAnalyzer.get_power_factor()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapAnalyzer.get_power_factor)


            * [`BoltztrapAnalyzer.get_seebeck()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapAnalyzer.get_seebeck)


            * [`BoltztrapAnalyzer.get_seebeck_eff_mass()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapAnalyzer.get_seebeck_eff_mass)


            * [`BoltztrapAnalyzer.get_symm_bands()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapAnalyzer.get_symm_bands)


            * [`BoltztrapAnalyzer.get_thermal_conductivity()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapAnalyzer.get_thermal_conductivity)


            * [`BoltztrapAnalyzer.get_zt()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapAnalyzer.get_zt)


            * [`BoltztrapAnalyzer.parse_cond_and_hall()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapAnalyzer.parse_cond_and_hall)


            * [`BoltztrapAnalyzer.parse_intrans()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapAnalyzer.parse_intrans)


            * [`BoltztrapAnalyzer.parse_outputtrans()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapAnalyzer.parse_outputtrans)


            * [`BoltztrapAnalyzer.parse_struct()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapAnalyzer.parse_struct)


            * [`BoltztrapAnalyzer.parse_transdos()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapAnalyzer.parse_transdos)


        * [`BoltztrapError`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapError)


        * [`BoltztrapRunner`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapRunner)


            * [`BoltztrapRunner._auto_set_energy_range()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapRunner._auto_set_energy_range)


            * [`BoltztrapRunner.as_dict()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapRunner.as_dict)


            * [`BoltztrapRunner.bs`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapRunner.bs)


            * [`BoltztrapRunner.nelec`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapRunner.nelec)


            * [`BoltztrapRunner.run()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapRunner.run)


            * [`BoltztrapRunner.write_def()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapRunner.write_def)


            * [`BoltztrapRunner.write_energy()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapRunner.write_energy)


            * [`BoltztrapRunner.write_input()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapRunner.write_input)


            * [`BoltztrapRunner.write_intrans()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapRunner.write_intrans)


            * [`BoltztrapRunner.write_proj()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapRunner.write_proj)


            * [`BoltztrapRunner.write_struct()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.BoltztrapRunner.write_struct)


        * [`compare_sym_bands()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.compare_sym_bands)


        * [`eta_from_seebeck()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.eta_from_seebeck)


        * [`read_cube_file()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.read_cube_file)


        * [`seebeck_eff_mass_from_carr()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.seebeck_eff_mass_from_carr)


        * [`seebeck_eff_mass_from_seebeck_carr()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.seebeck_eff_mass_from_seebeck_carr)


        * [`seebeck_spb()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap.seebeck_spb)


    * [pymatgen.electronic_structure.boltztrap2 module](pymatgen.electronic_structure.md#module-pymatgen.electronic_structure.boltztrap2)


        * [`BandstructureLoader`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap2.BandstructureLoader)


            * [`BandstructureLoader.bandana()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap2.BandstructureLoader.bandana)


            * [`BandstructureLoader.get_lattvec()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap2.BandstructureLoader.get_lattvec)


            * [`BandstructureLoader.get_volume()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap2.BandstructureLoader.get_volume)


            * [`BandstructureLoader.set_upper_lower_bands()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap2.BandstructureLoader.set_upper_lower_bands)


        * [`BztInterpolator`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap2.BztInterpolator)


            * [`BztInterpolator.get_band_structure()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap2.BztInterpolator.get_band_structure)


            * [`BztInterpolator.get_dos()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap2.BztInterpolator.get_dos)


            * [`BztInterpolator.get_partial_doses()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap2.BztInterpolator.get_partial_doses)


            * [`BztInterpolator.load()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap2.BztInterpolator.load)


            * [`BztInterpolator.save()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap2.BztInterpolator.save)


        * [`BztPlotter`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap2.BztPlotter)


            * [`BztPlotter.plot_bands()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap2.BztPlotter.plot_bands)


            * [`BztPlotter.plot_dos()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap2.BztPlotter.plot_dos)


            * [`BztPlotter.plot_props()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap2.BztPlotter.plot_props)


        * [`BztTransportProperties`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap2.BztTransportProperties)


            * [`BztTransportProperties.compute_properties_doping()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap2.BztTransportProperties.compute_properties_doping)


            * [`BztTransportProperties.load()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap2.BztTransportProperties.load)


            * [`BztTransportProperties.save()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap2.BztTransportProperties.save)


        * [`VasprunBSLoader`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap2.VasprunBSLoader)


            * [`VasprunBSLoader.bandana()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap2.VasprunBSLoader.bandana)


            * [`VasprunBSLoader.from_file()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap2.VasprunBSLoader.from_file)


            * [`VasprunBSLoader.get_lattvec()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap2.VasprunBSLoader.get_lattvec)


            * [`VasprunBSLoader.get_volume()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap2.VasprunBSLoader.get_volume)


        * [`VasprunLoader`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap2.VasprunLoader)


            * [`VasprunLoader.bandana()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap2.VasprunLoader.bandana)


            * [`VasprunLoader.from_file()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap2.VasprunLoader.from_file)


            * [`VasprunLoader.get_lattvec()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap2.VasprunLoader.get_lattvec)


            * [`VasprunLoader.get_volume()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap2.VasprunLoader.get_volume)


        * [`merge_up_down_doses()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.boltztrap2.merge_up_down_doses)


    * [pymatgen.electronic_structure.cohp module](pymatgen.electronic_structure.md#module-pymatgen.electronic_structure.cohp)


        * [`Cohp`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.Cohp)


            * [`Cohp.as_dict()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.Cohp.as_dict)


            * [`Cohp.from_dict()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.Cohp.from_dict)


            * [`Cohp.get_cohp()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.Cohp.get_cohp)


            * [`Cohp.get_icohp()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.Cohp.get_icohp)


            * [`Cohp.get_interpolated_value()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.Cohp.get_interpolated_value)


            * [`Cohp.has_antibnd_states_below_efermi()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.Cohp.has_antibnd_states_below_efermi)


        * [`CompleteCohp`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.CompleteCohp)


            * [`CompleteCohp.are_coops`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.CompleteCohp.are_coops)


            * [`CompleteCohp.are_cobis`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.CompleteCohp.are_cobis)


            * [`CompleteCohp.efermi`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.CompleteCohp.efermi)


            * [`CompleteCohp.energies`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.CompleteCohp.energies)


            * [`CompleteCohp.structure`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.CompleteCohp.structure)


            * [`CompleteCohp.cohp`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.CompleteCohp.cohp)


            * [`CompleteCohp.icohp`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.CompleteCohp.icohp)


            * [`CompleteCohp.all_cohps`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.CompleteCohp.all_cohps)


            * [`CompleteCohp.orb_res_cohp`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.CompleteCohp.orb_res_cohp)


            * [`CompleteCohp.as_dict()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.CompleteCohp.as_dict)


            * [`CompleteCohp.from_dict()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.CompleteCohp.from_dict)


            * [`CompleteCohp.from_file()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.CompleteCohp.from_file)


            * [`CompleteCohp.get_cohp_by_label()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.CompleteCohp.get_cohp_by_label)


            * [`CompleteCohp.get_orbital_resolved_cohp()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.CompleteCohp.get_orbital_resolved_cohp)


            * [`CompleteCohp.get_summed_cohp_by_label_and_orbital_list()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.CompleteCohp.get_summed_cohp_by_label_and_orbital_list)


            * [`CompleteCohp.get_summed_cohp_by_label_list()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.CompleteCohp.get_summed_cohp_by_label_list)


        * [`IcohpCollection`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.IcohpCollection)


            * [`IcohpCollection.are_coops`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.IcohpCollection.are_coops)


            * [`IcohpCollection.are_cobis`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.IcohpCollection.are_cobis)


            * [`IcohpCollection.is_spin_polarized`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.IcohpCollection.is_spin_polarized)


            * [`IcohpCollection.are_cobis`](pymatgen.electronic_structure.md#id0)


            * [`IcohpCollection.are_coops`](pymatgen.electronic_structure.md#id1)


            * [`IcohpCollection.extremum_icohpvalue()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.IcohpCollection.extremum_icohpvalue)


            * [`IcohpCollection.get_icohp_by_label()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.IcohpCollection.get_icohp_by_label)


            * [`IcohpCollection.get_icohp_dict_by_bondlengths()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.IcohpCollection.get_icohp_dict_by_bondlengths)


            * [`IcohpCollection.get_icohp_dict_of_site()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.IcohpCollection.get_icohp_dict_of_site)


            * [`IcohpCollection.get_summed_icohp_by_label_list()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.IcohpCollection.get_summed_icohp_by_label_list)


            * [`IcohpCollection.is_spin_polarized`](pymatgen.electronic_structure.md#id2)


        * [`IcohpValue`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.IcohpValue)


            * [`IcohpValue.energies`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.IcohpValue.energies)


            * [`IcohpValue.densities`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.IcohpValue.densities)


            * [`IcohpValue.energies_are_cartesian`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.IcohpValue.energies_are_cartesian)


            * [`IcohpValue.are_coops`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.IcohpValue.are_coops)


            * [`IcohpValue.are_cobis`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.IcohpValue.are_cobis)


            * [`IcohpValue.icohp`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.IcohpValue.icohp)


            * [`IcohpValue.summed_icohp`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.IcohpValue.summed_icohp)


            * [`IcohpValue.num_bonds`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.IcohpValue.num_bonds)


            * [`IcohpValue.are_cobis`](pymatgen.electronic_structure.md#id3)


            * [`IcohpValue.are_coops`](pymatgen.electronic_structure.md#id4)


            * [`IcohpValue.icohp`](pymatgen.electronic_structure.md#id5)


            * [`IcohpValue.icohpvalue()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.IcohpValue.icohpvalue)


            * [`IcohpValue.icohpvalue_orbital()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.IcohpValue.icohpvalue_orbital)


            * [`IcohpValue.is_spin_polarized`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.IcohpValue.is_spin_polarized)


            * [`IcohpValue.num_bonds`](pymatgen.electronic_structure.md#id6)


            * [`IcohpValue.summed_icohp`](pymatgen.electronic_structure.md#id7)


            * [`IcohpValue.summed_orbital_icohp`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.IcohpValue.summed_orbital_icohp)


        * [`get_integrated_cohp_in_energy_range()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.cohp.get_integrated_cohp_in_energy_range)


    * [pymatgen.electronic_structure.core module](pymatgen.electronic_structure.md#module-pymatgen.electronic_structure.core)


        * [`Magmom`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Magmom)


            * [`Magmom._get_transformation_matrix()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Magmom._get_transformation_matrix)


            * [`Magmom._get_transformation_matrix_inv()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Magmom._get_transformation_matrix_inv)


            * [`Magmom.are_collinear()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Magmom.are_collinear)


            * [`Magmom.from_global_moment_and_saxis()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Magmom.from_global_moment_and_saxis)


            * [`Magmom.from_moment_relative_to_crystal_axes()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Magmom.from_moment_relative_to_crystal_axes)


            * [`Magmom.get_00t_magmom_with_xyz_saxis()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Magmom.get_00t_magmom_with_xyz_saxis)


            * [`Magmom.get_consistent_set_and_saxis()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Magmom.get_consistent_set_and_saxis)


            * [`Magmom.get_moment()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Magmom.get_moment)


            * [`Magmom.get_moment_relative_to_crystal_axes()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Magmom.get_moment_relative_to_crystal_axes)


            * [`Magmom.get_suggested_saxis()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Magmom.get_suggested_saxis)


            * [`Magmom.get_xyz_magmom_with_001_saxis()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Magmom.get_xyz_magmom_with_001_saxis)


            * [`Magmom.global_moment`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Magmom.global_moment)


            * [`Magmom.have_consistent_saxis()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Magmom.have_consistent_saxis)


            * [`Magmom.projection`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Magmom.projection)


        * [`Orbital`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Orbital)


            * [`Orbital.dx2`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Orbital.dx2)


            * [`Orbital.dxy`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Orbital.dxy)


            * [`Orbital.dxz`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Orbital.dxz)


            * [`Orbital.dyz`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Orbital.dyz)


            * [`Orbital.dz2`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Orbital.dz2)


            * [`Orbital.f0`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Orbital.f0)


            * [`Orbital.f1`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Orbital.f1)


            * [`Orbital.f2`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Orbital.f2)


            * [`Orbital.f3`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Orbital.f3)


            * [`Orbital.f_1`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Orbital.f_1)


            * [`Orbital.f_2`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Orbital.f_2)


            * [`Orbital.f_3`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Orbital.f_3)


            * [`Orbital.orbital_type`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Orbital.orbital_type)


            * [`Orbital.px`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Orbital.px)


            * [`Orbital.py`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Orbital.py)


            * [`Orbital.pz`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Orbital.pz)


            * [`Orbital.s`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Orbital.s)


        * [`OrbitalType`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.OrbitalType)


            * [`OrbitalType.d`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.OrbitalType.d)


            * [`OrbitalType.f`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.OrbitalType.f)


            * [`OrbitalType.p`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.OrbitalType.p)


            * [`OrbitalType.s`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.OrbitalType.s)


        * [`Spin`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Spin)


            * [`Spin.down`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Spin.down)


            * [`Spin.up`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.core.Spin.up)


    * [pymatgen.electronic_structure.dos module](pymatgen.electronic_structure.md#module-pymatgen.electronic_structure.dos)


        * [`CompleteDos`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.CompleteDos)


            * [`CompleteDos.structure`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.CompleteDos.structure)


            * [`CompleteDos.pdos`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.CompleteDos.pdos)


            * [`CompleteDos.as_dict()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.CompleteDos.as_dict)


            * [`CompleteDos.fp_to_dict()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.CompleteDos.fp_to_dict)


            * [`CompleteDos.from_dict()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.CompleteDos.from_dict)


            * [`CompleteDos.get_band_center()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.CompleteDos.get_band_center)


            * [`CompleteDos.get_band_filling()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.CompleteDos.get_band_filling)


            * [`CompleteDos.get_band_kurtosis()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.CompleteDos.get_band_kurtosis)


            * [`CompleteDos.get_band_skewness()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.CompleteDos.get_band_skewness)


            * [`CompleteDos.get_band_width()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.CompleteDos.get_band_width)


            * [`CompleteDos.get_dos_fp()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.CompleteDos.get_dos_fp)


            * [`CompleteDos.get_dos_fp_similarity()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.CompleteDos.get_dos_fp_similarity)


            * [`CompleteDos.get_element_dos()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.CompleteDos.get_element_dos)


            * [`CompleteDos.get_element_spd_dos()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.CompleteDos.get_element_spd_dos)


            * [`CompleteDos.get_hilbert_transform()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.CompleteDos.get_hilbert_transform)


            * [`CompleteDos.get_n_moment()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.CompleteDos.get_n_moment)


            * [`CompleteDos.get_normalized()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.CompleteDos.get_normalized)


            * [`CompleteDos.get_site_dos()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.CompleteDos.get_site_dos)


            * [`CompleteDos.get_site_orbital_dos()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.CompleteDos.get_site_orbital_dos)


            * [`CompleteDos.get_site_spd_dos()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.CompleteDos.get_site_spd_dos)


            * [`CompleteDos.get_site_t2g_eg_resolved_dos()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.CompleteDos.get_site_t2g_eg_resolved_dos)


            * [`CompleteDos.get_spd_dos()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.CompleteDos.get_spd_dos)


            * [`CompleteDos.get_upper_band_edge()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.CompleteDos.get_upper_band_edge)


            * [`CompleteDos.spin_polarization`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.CompleteDos.spin_polarization)


        * [`DOS`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.DOS)


            * [`DOS.energies`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.DOS.energies)


            * [`DOS.densities`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.DOS.densities)


            * [`DOS.efermi`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.DOS.efermi)


            * [`DOS.XLABEL`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.DOS.XLABEL)


            * [`DOS.YLABEL`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.DOS.YLABEL)


            * [`DOS.get_cbm_vbm()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.DOS.get_cbm_vbm)


            * [`DOS.get_gap()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.DOS.get_gap)


            * [`DOS.get_interpolated_gap()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.DOS.get_interpolated_gap)


        * [`Dos`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.Dos)


            * [`Dos.energies`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.Dos.energies)


            * [`Dos.densities`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.Dos.densities)


            * [`Dos.efermi`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.Dos.efermi)


            * [`Dos.as_dict()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.Dos.as_dict)


            * [`Dos.from_dict()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.Dos.from_dict)


            * [`Dos.get_cbm_vbm()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.Dos.get_cbm_vbm)


            * [`Dos.get_densities()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.Dos.get_densities)


            * [`Dos.get_gap()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.Dos.get_gap)


            * [`Dos.get_interpolated_gap()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.Dos.get_interpolated_gap)


            * [`Dos.get_interpolated_value()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.Dos.get_interpolated_value)


            * [`Dos.get_smeared_densities()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.Dos.get_smeared_densities)


        * [`FermiDos`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.FermiDos)


            * [`FermiDos.as_dict()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.FermiDos.as_dict)


            * [`FermiDos.from_dict()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.FermiDos.from_dict)


            * [`FermiDos.get_doping()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.FermiDos.get_doping)


            * [`FermiDos.get_fermi()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.FermiDos.get_fermi)


            * [`FermiDos.get_fermi_interextrapolated()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.FermiDos.get_fermi_interextrapolated)


        * [`LobsterCompleteDos`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.LobsterCompleteDos)


            * [`LobsterCompleteDos.from_dict()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.LobsterCompleteDos.from_dict)


            * [`LobsterCompleteDos.get_element_spd_dos()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.LobsterCompleteDos.get_element_spd_dos)


            * [`LobsterCompleteDos.get_site_orbital_dos()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.LobsterCompleteDos.get_site_orbital_dos)


            * [`LobsterCompleteDos.get_site_t2g_eg_resolved_dos()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.LobsterCompleteDos.get_site_t2g_eg_resolved_dos)


            * [`LobsterCompleteDos.get_spd_dos()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.LobsterCompleteDos.get_spd_dos)


        * [`_get_orb_lobster()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos._get_orb_lobster)


        * [`_get_orb_type()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos._get_orb_type)


        * [`_get_orb_type_lobster()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos._get_orb_type_lobster)


        * [`add_densities()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.add_densities)


        * [`f0()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.dos.f0)


    * [pymatgen.electronic_structure.plotter module](pymatgen.electronic_structure.md#module-pymatgen.electronic_structure.plotter)


        * [`BSDOSPlotter`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSDOSPlotter)


            * [`BSDOSPlotter._cmyk_triangle()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSDOSPlotter._cmyk_triangle)


            * [`BSDOSPlotter._get_colordata()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSDOSPlotter._get_colordata)


            * [`BSDOSPlotter._rb_line()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSDOSPlotter._rb_line)


            * [`BSDOSPlotter._rgb_triangle()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSDOSPlotter._rgb_triangle)


            * [`BSDOSPlotter._rgbline()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSDOSPlotter._rgbline)


            * [`BSDOSPlotter.get_plot()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSDOSPlotter.get_plot)


        * [`BSPlotter`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSPlotter)


            * [`BSPlotter._check_bs_kpath()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSPlotter._check_bs_kpath)


            * [`BSPlotter._get_branch_steps()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSPlotter._get_branch_steps)


            * [`BSPlotter._interpolate_bands()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSPlotter._interpolate_bands)


            * [`BSPlotter._make_ticks()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSPlotter._make_ticks)


            * [`BSPlotter._rescale_distances()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSPlotter._rescale_distances)


            * [`BSPlotter.add_bs()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSPlotter.add_bs)


            * [`BSPlotter.bs_plot_data()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSPlotter.bs_plot_data)


            * [`BSPlotter.get_plot()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSPlotter.get_plot)


            * [`BSPlotter.get_ticks()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSPlotter.get_ticks)


            * [`BSPlotter.get_ticks_old()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSPlotter.get_ticks_old)


            * [`BSPlotter.plot_brillouin()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSPlotter.plot_brillouin)


            * [`BSPlotter.plot_compare()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSPlotter.plot_compare)


            * [`BSPlotter.save_plot()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSPlotter.save_plot)


            * [`BSPlotter.show()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSPlotter.show)


        * [`BSPlotterProjected`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSPlotterProjected)


            * [`BSPlotterProjected._Orbitals_SumOrbitals()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSPlotterProjected._Orbitals_SumOrbitals)


            * [`BSPlotterProjected._get_projections_by_branches()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSPlotterProjected._get_projections_by_branches)


            * [`BSPlotterProjected._get_projections_by_branches_patom_pmorb()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSPlotterProjected._get_projections_by_branches_patom_pmorb)


            * [`BSPlotterProjected._make_ticks_selected()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSPlotterProjected._make_ticks_selected)


            * [`BSPlotterProjected._number_of_subfigures()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSPlotterProjected._number_of_subfigures)


            * [`BSPlotterProjected._summarize_keys_for_plot()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSPlotterProjected._summarize_keys_for_plot)


            * [`BSPlotterProjected.get_elt_projected_plots()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSPlotterProjected.get_elt_projected_plots)


            * [`BSPlotterProjected.get_elt_projected_plots_color()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSPlotterProjected.get_elt_projected_plots_color)


            * [`BSPlotterProjected.get_projected_plots_dots()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSPlotterProjected.get_projected_plots_dots)


            * [`BSPlotterProjected.get_projected_plots_dots_patom_pmorb()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BSPlotterProjected.get_projected_plots_dots_patom_pmorb)


        * [`BoltztrapPlotter`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BoltztrapPlotter)


            * [`BoltztrapPlotter._plot_bg_limits()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BoltztrapPlotter._plot_bg_limits)


            * [`BoltztrapPlotter._plot_doping()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BoltztrapPlotter._plot_doping)


            * [`BoltztrapPlotter.plot_carriers()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BoltztrapPlotter.plot_carriers)


            * [`BoltztrapPlotter.plot_complexity_factor_mu()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BoltztrapPlotter.plot_complexity_factor_mu)


            * [`BoltztrapPlotter.plot_conductivity_dop()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BoltztrapPlotter.plot_conductivity_dop)


            * [`BoltztrapPlotter.plot_conductivity_mu()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BoltztrapPlotter.plot_conductivity_mu)


            * [`BoltztrapPlotter.plot_conductivity_temp()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BoltztrapPlotter.plot_conductivity_temp)


            * [`BoltztrapPlotter.plot_dos()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BoltztrapPlotter.plot_dos)


            * [`BoltztrapPlotter.plot_eff_mass_dop()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BoltztrapPlotter.plot_eff_mass_dop)


            * [`BoltztrapPlotter.plot_eff_mass_temp()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BoltztrapPlotter.plot_eff_mass_temp)


            * [`BoltztrapPlotter.plot_hall_carriers()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BoltztrapPlotter.plot_hall_carriers)


            * [`BoltztrapPlotter.plot_power_factor_dop()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BoltztrapPlotter.plot_power_factor_dop)


            * [`BoltztrapPlotter.plot_power_factor_mu()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BoltztrapPlotter.plot_power_factor_mu)


            * [`BoltztrapPlotter.plot_power_factor_temp()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BoltztrapPlotter.plot_power_factor_temp)


            * [`BoltztrapPlotter.plot_seebeck_dop()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BoltztrapPlotter.plot_seebeck_dop)


            * [`BoltztrapPlotter.plot_seebeck_eff_mass_mu()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BoltztrapPlotter.plot_seebeck_eff_mass_mu)


            * [`BoltztrapPlotter.plot_seebeck_mu()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BoltztrapPlotter.plot_seebeck_mu)


            * [`BoltztrapPlotter.plot_seebeck_temp()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BoltztrapPlotter.plot_seebeck_temp)


            * [`BoltztrapPlotter.plot_zt_dop()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BoltztrapPlotter.plot_zt_dop)


            * [`BoltztrapPlotter.plot_zt_mu()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BoltztrapPlotter.plot_zt_mu)


            * [`BoltztrapPlotter.plot_zt_temp()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.BoltztrapPlotter.plot_zt_temp)


        * [`CohpPlotter`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.CohpPlotter)


            * [`CohpPlotter.add_cohp()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.CohpPlotter.add_cohp)


            * [`CohpPlotter.add_cohp_dict()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.CohpPlotter.add_cohp_dict)


            * [`CohpPlotter.get_cohp_dict()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.CohpPlotter.get_cohp_dict)


            * [`CohpPlotter.get_plot()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.CohpPlotter.get_plot)


            * [`CohpPlotter.save_plot()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.CohpPlotter.save_plot)


            * [`CohpPlotter.show()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.CohpPlotter.show)


        * [`DosPlotter`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.DosPlotter)


            * [`DosPlotter.add_dos()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.DosPlotter.add_dos)


            * [`DosPlotter.add_dos_dict()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.DosPlotter.add_dos_dict)


            * [`DosPlotter.get_dos_dict()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.DosPlotter.get_dos_dict)


            * [`DosPlotter.get_plot()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.DosPlotter.get_plot)


            * [`DosPlotter.save_plot()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.DosPlotter.save_plot)


            * [`DosPlotter.show()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.DosPlotter.show)


        * [`fold_point()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.fold_point)


        * [`plot_brillouin_zone()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.plot_brillouin_zone)


        * [`plot_brillouin_zone_from_kpath()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.plot_brillouin_zone_from_kpath)


        * [`plot_ellipsoid()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.plot_ellipsoid)


        * [`plot_fermi_surface()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.plot_fermi_surface)


        * [`plot_labels()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.plot_labels)


        * [`plot_lattice_vectors()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.plot_lattice_vectors)


        * [`plot_path()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.plot_path)


        * [`plot_points()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.plot_points)


        * [`plot_wigner_seitz()`](pymatgen.electronic_structure.md#pymatgen.electronic_structure.plotter.plot_wigner_seitz)


* [pymatgen.entries package](pymatgen.entries.md)


    * [`Entry`](pymatgen.entries.md#pymatgen.entries.Entry)


        * [`Entry._abc_impl`](pymatgen.entries.md#pymatgen.entries.Entry._abc_impl)


        * [`Entry._normalization_factor()`](pymatgen.entries.md#pymatgen.entries.Entry._normalization_factor)


        * [`Entry.as_dict()`](pymatgen.entries.md#pymatgen.entries.Entry.as_dict)


        * [`Entry.composition`](pymatgen.entries.md#pymatgen.entries.Entry.composition)


        * [`Entry.elements`](pymatgen.entries.md#pymatgen.entries.Entry.elements)


        * [`Entry.energy`](pymatgen.entries.md#pymatgen.entries.Entry.energy)


        * [`Entry.energy_per_atom`](pymatgen.entries.md#pymatgen.entries.Entry.energy_per_atom)


        * [`Entry.is_element`](pymatgen.entries.md#pymatgen.entries.Entry.is_element)


        * [`Entry.normalize()`](pymatgen.entries.md#pymatgen.entries.Entry.normalize)




    * [pymatgen.entries.compatibility module](pymatgen.entries.md#module-pymatgen.entries.compatibility)


        * [`AnionCorrection`](pymatgen.entries.md#pymatgen.entries.compatibility.AnionCorrection)


            * [`AnionCorrection._abc_impl`](pymatgen.entries.md#pymatgen.entries.compatibility.AnionCorrection._abc_impl)


        * [`AqueousCorrection`](pymatgen.entries.md#pymatgen.entries.compatibility.AqueousCorrection)


            * [`AqueousCorrection._abc_impl`](pymatgen.entries.md#pymatgen.entries.compatibility.AqueousCorrection._abc_impl)


        * [`Compatibility`](pymatgen.entries.md#pymatgen.entries.compatibility.Compatibility)


            * [`Compatibility._abc_impl`](pymatgen.entries.md#pymatgen.entries.compatibility.Compatibility._abc_impl)


            * [`Compatibility.explain()`](pymatgen.entries.md#pymatgen.entries.compatibility.Compatibility.explain)


            * [`Compatibility.get_adjustments()`](pymatgen.entries.md#pymatgen.entries.compatibility.Compatibility.get_adjustments)


            * [`Compatibility.process_entries()`](pymatgen.entries.md#pymatgen.entries.compatibility.Compatibility.process_entries)


            * [`Compatibility.process_entry()`](pymatgen.entries.md#pymatgen.entries.compatibility.Compatibility.process_entry)


        * [`CompatibilityError`](pymatgen.entries.md#pymatgen.entries.compatibility.CompatibilityError)


        * [`Correction`](pymatgen.entries.md#pymatgen.entries.compatibility.Correction)


            * [`Correction._abc_impl`](pymatgen.entries.md#pymatgen.entries.compatibility.Correction._abc_impl)


            * [`Correction.correct_entry()`](pymatgen.entries.md#pymatgen.entries.compatibility.Correction.correct_entry)


            * [`Correction.get_correction()`](pymatgen.entries.md#pymatgen.entries.compatibility.Correction.get_correction)


        * [`CorrectionsList`](pymatgen.entries.md#pymatgen.entries.compatibility.CorrectionsList)


            * [`CorrectionsList._abc_impl`](pymatgen.entries.md#pymatgen.entries.compatibility.CorrectionsList._abc_impl)


            * [`CorrectionsList.explain()`](pymatgen.entries.md#pymatgen.entries.compatibility.CorrectionsList.explain)


            * [`CorrectionsList.get_adjustments()`](pymatgen.entries.md#pymatgen.entries.compatibility.CorrectionsList.get_adjustments)


            * [`CorrectionsList.get_corrections_dict()`](pymatgen.entries.md#pymatgen.entries.compatibility.CorrectionsList.get_corrections_dict)


            * [`CorrectionsList.get_explanation_dict()`](pymatgen.entries.md#pymatgen.entries.compatibility.CorrectionsList.get_explanation_dict)


        * [`GasCorrection`](pymatgen.entries.md#pymatgen.entries.compatibility.GasCorrection)


            * [`GasCorrection._abc_impl`](pymatgen.entries.md#pymatgen.entries.compatibility.GasCorrection._abc_impl)


        * [`MITAqueousCompatibility`](pymatgen.entries.md#pymatgen.entries.compatibility.MITAqueousCompatibility)


            * [`MITAqueousCompatibility._abc_impl`](pymatgen.entries.md#pymatgen.entries.compatibility.MITAqueousCompatibility._abc_impl)


        * [`MITCompatibility`](pymatgen.entries.md#pymatgen.entries.compatibility.MITCompatibility)


            * [`MITCompatibility._abc_impl`](pymatgen.entries.md#pymatgen.entries.compatibility.MITCompatibility._abc_impl)


        * [`MaterialsProject2020Compatibility`](pymatgen.entries.md#pymatgen.entries.compatibility.MaterialsProject2020Compatibility)


            * [`MaterialsProject2020Compatibility._abc_impl`](pymatgen.entries.md#pymatgen.entries.compatibility.MaterialsProject2020Compatibility._abc_impl)


        * [`MaterialsProjectAqueousCompatibility`](pymatgen.entries.md#pymatgen.entries.compatibility.MaterialsProjectAqueousCompatibility)


            * [`MaterialsProjectAqueousCompatibility._abc_impl`](pymatgen.entries.md#pymatgen.entries.compatibility.MaterialsProjectAqueousCompatibility._abc_impl)


        * [`MaterialsProjectCompatibility`](pymatgen.entries.md#pymatgen.entries.compatibility.MaterialsProjectCompatibility)


            * [`MaterialsProjectCompatibility._abc_impl`](pymatgen.entries.md#pymatgen.entries.compatibility.MaterialsProjectCompatibility._abc_impl)


        * [`PotcarCorrection`](pymatgen.entries.md#pymatgen.entries.compatibility.PotcarCorrection)


            * [`PotcarCorrection._abc_impl`](pymatgen.entries.md#pymatgen.entries.compatibility.PotcarCorrection._abc_impl)


            * [`PotcarCorrection.get_correction()`](pymatgen.entries.md#pymatgen.entries.compatibility.PotcarCorrection.get_correction)


        * [`UCorrection`](pymatgen.entries.md#pymatgen.entries.compatibility.UCorrection)


            * [`UCorrection._abc_impl`](pymatgen.entries.md#pymatgen.entries.compatibility.UCorrection._abc_impl)


    * [pymatgen.entries.computed_entries module](pymatgen.entries.md#module-pymatgen.entries.computed_entries)


        * [`CompositionEnergyAdjustment`](pymatgen.entries.md#pymatgen.entries.computed_entries.CompositionEnergyAdjustment)


            * [`CompositionEnergyAdjustment.explain`](pymatgen.entries.md#pymatgen.entries.computed_entries.CompositionEnergyAdjustment.explain)


            * [`CompositionEnergyAdjustment.normalize()`](pymatgen.entries.md#pymatgen.entries.computed_entries.CompositionEnergyAdjustment.normalize)


            * [`CompositionEnergyAdjustment.uncertainty`](pymatgen.entries.md#pymatgen.entries.computed_entries.CompositionEnergyAdjustment.uncertainty)


            * [`CompositionEnergyAdjustment.value`](pymatgen.entries.md#pymatgen.entries.computed_entries.CompositionEnergyAdjustment.value)


        * [`ComputedEntry`](pymatgen.entries.md#pymatgen.entries.computed_entries.ComputedEntry)


            * [`ComputedEntry._abc_impl`](pymatgen.entries.md#pymatgen.entries.computed_entries.ComputedEntry._abc_impl)


            * [`ComputedEntry.as_dict()`](pymatgen.entries.md#pymatgen.entries.computed_entries.ComputedEntry.as_dict)


            * [`ComputedEntry.copy()`](pymatgen.entries.md#pymatgen.entries.computed_entries.ComputedEntry.copy)


            * [`ComputedEntry.correction`](pymatgen.entries.md#pymatgen.entries.computed_entries.ComputedEntry.correction)


            * [`ComputedEntry.correction_per_atom`](pymatgen.entries.md#pymatgen.entries.computed_entries.ComputedEntry.correction_per_atom)


            * [`ComputedEntry.correction_uncertainty`](pymatgen.entries.md#pymatgen.entries.computed_entries.ComputedEntry.correction_uncertainty)


            * [`ComputedEntry.correction_uncertainty_per_atom`](pymatgen.entries.md#pymatgen.entries.computed_entries.ComputedEntry.correction_uncertainty_per_atom)


            * [`ComputedEntry.energy`](pymatgen.entries.md#pymatgen.entries.computed_entries.ComputedEntry.energy)


            * [`ComputedEntry.from_dict()`](pymatgen.entries.md#pymatgen.entries.computed_entries.ComputedEntry.from_dict)


            * [`ComputedEntry.normalize()`](pymatgen.entries.md#pymatgen.entries.computed_entries.ComputedEntry.normalize)


            * [`ComputedEntry.uncorrected_energy`](pymatgen.entries.md#pymatgen.entries.computed_entries.ComputedEntry.uncorrected_energy)


            * [`ComputedEntry.uncorrected_energy_per_atom`](pymatgen.entries.md#pymatgen.entries.computed_entries.ComputedEntry.uncorrected_energy_per_atom)


        * [`ComputedStructureEntry`](pymatgen.entries.md#pymatgen.entries.computed_entries.ComputedStructureEntry)


            * [`ComputedStructureEntry._abc_impl`](pymatgen.entries.md#pymatgen.entries.computed_entries.ComputedStructureEntry._abc_impl)


            * [`ComputedStructureEntry.as_dict()`](pymatgen.entries.md#pymatgen.entries.computed_entries.ComputedStructureEntry.as_dict)


            * [`ComputedStructureEntry.copy()`](pymatgen.entries.md#pymatgen.entries.computed_entries.ComputedStructureEntry.copy)


            * [`ComputedStructureEntry.from_dict()`](pymatgen.entries.md#pymatgen.entries.computed_entries.ComputedStructureEntry.from_dict)


            * [`ComputedStructureEntry.normalize()`](pymatgen.entries.md#pymatgen.entries.computed_entries.ComputedStructureEntry.normalize)


            * [`ComputedStructureEntry.structure`](pymatgen.entries.md#pymatgen.entries.computed_entries.ComputedStructureEntry.structure)


        * [`ConstantEnergyAdjustment`](pymatgen.entries.md#pymatgen.entries.computed_entries.ConstantEnergyAdjustment)


            * [`ConstantEnergyAdjustment.explain`](pymatgen.entries.md#pymatgen.entries.computed_entries.ConstantEnergyAdjustment.explain)


            * [`ConstantEnergyAdjustment.normalize()`](pymatgen.entries.md#pymatgen.entries.computed_entries.ConstantEnergyAdjustment.normalize)


        * [`EnergyAdjustment`](pymatgen.entries.md#pymatgen.entries.computed_entries.EnergyAdjustment)


            * [`EnergyAdjustment.explain`](pymatgen.entries.md#pymatgen.entries.computed_entries.EnergyAdjustment.explain)


            * [`EnergyAdjustment.normalize()`](pymatgen.entries.md#pymatgen.entries.computed_entries.EnergyAdjustment.normalize)


            * [`EnergyAdjustment.uncertainty`](pymatgen.entries.md#pymatgen.entries.computed_entries.EnergyAdjustment.uncertainty)


            * [`EnergyAdjustment.value`](pymatgen.entries.md#pymatgen.entries.computed_entries.EnergyAdjustment.value)


        * [`GibbsComputedStructureEntry`](pymatgen.entries.md#pymatgen.entries.computed_entries.GibbsComputedStructureEntry)


            * [`GibbsComputedStructureEntry._abc_impl`](pymatgen.entries.md#pymatgen.entries.computed_entries.GibbsComputedStructureEntry._abc_impl)


            * [`GibbsComputedStructureEntry._g_delta_sisso()`](pymatgen.entries.md#pymatgen.entries.computed_entries.GibbsComputedStructureEntry._g_delta_sisso)


            * [`GibbsComputedStructureEntry._reduced_mass()`](pymatgen.entries.md#pymatgen.entries.computed_entries.GibbsComputedStructureEntry._reduced_mass)


            * [`GibbsComputedStructureEntry._sum_g_i()`](pymatgen.entries.md#pymatgen.entries.computed_entries.GibbsComputedStructureEntry._sum_g_i)


            * [`GibbsComputedStructureEntry.as_dict()`](pymatgen.entries.md#pymatgen.entries.computed_entries.GibbsComputedStructureEntry.as_dict)


            * [`GibbsComputedStructureEntry.from_dict()`](pymatgen.entries.md#pymatgen.entries.computed_entries.GibbsComputedStructureEntry.from_dict)


            * [`GibbsComputedStructureEntry.from_entries()`](pymatgen.entries.md#pymatgen.entries.computed_entries.GibbsComputedStructureEntry.from_entries)


            * [`GibbsComputedStructureEntry.from_pd()`](pymatgen.entries.md#pymatgen.entries.computed_entries.GibbsComputedStructureEntry.from_pd)


            * [`GibbsComputedStructureEntry.gf_sisso()`](pymatgen.entries.md#pymatgen.entries.computed_entries.GibbsComputedStructureEntry.gf_sisso)


        * [`ManualEnergyAdjustment`](pymatgen.entries.md#pymatgen.entries.computed_entries.ManualEnergyAdjustment)


        * [`TemperatureEnergyAdjustment`](pymatgen.entries.md#pymatgen.entries.computed_entries.TemperatureEnergyAdjustment)


            * [`TemperatureEnergyAdjustment.explain`](pymatgen.entries.md#pymatgen.entries.computed_entries.TemperatureEnergyAdjustment.explain)


            * [`TemperatureEnergyAdjustment.normalize()`](pymatgen.entries.md#pymatgen.entries.computed_entries.TemperatureEnergyAdjustment.normalize)


            * [`TemperatureEnergyAdjustment.uncertainty`](pymatgen.entries.md#pymatgen.entries.computed_entries.TemperatureEnergyAdjustment.uncertainty)


            * [`TemperatureEnergyAdjustment.value`](pymatgen.entries.md#pymatgen.entries.computed_entries.TemperatureEnergyAdjustment.value)


    * [pymatgen.entries.correction_calculator module](pymatgen.entries.md#module-pymatgen.entries.correction_calculator)


        * [`CorrectionCalculator`](pymatgen.entries.md#pymatgen.entries.correction_calculator.CorrectionCalculator)


            * [`CorrectionCalculator.species`](pymatgen.entries.md#pymatgen.entries.correction_calculator.CorrectionCalculator.species)


            * [`CorrectionCalculator.exp_compounds`](pymatgen.entries.md#pymatgen.entries.correction_calculator.CorrectionCalculator.exp_compounds)


            * [`CorrectionCalculator.calc_compounds`](pymatgen.entries.md#pymatgen.entries.correction_calculator.CorrectionCalculator.calc_compounds)


            * [`CorrectionCalculator.corrections`](pymatgen.entries.md#pymatgen.entries.correction_calculator.CorrectionCalculator.corrections)


            * [`CorrectionCalculator.corrections_std_error`](pymatgen.entries.md#pymatgen.entries.correction_calculator.CorrectionCalculator.corrections_std_error)


            * [`CorrectionCalculator.corrections_dict`](pymatgen.entries.md#pymatgen.entries.correction_calculator.CorrectionCalculator.corrections_dict)


            * [`CorrectionCalculator.compute_corrections()`](pymatgen.entries.md#pymatgen.entries.correction_calculator.CorrectionCalculator.compute_corrections)


            * [`CorrectionCalculator.compute_from_files()`](pymatgen.entries.md#pymatgen.entries.correction_calculator.CorrectionCalculator.compute_from_files)


            * [`CorrectionCalculator.graph_residual_error()`](pymatgen.entries.md#pymatgen.entries.correction_calculator.CorrectionCalculator.graph_residual_error)


            * [`CorrectionCalculator.graph_residual_error_per_species()`](pymatgen.entries.md#pymatgen.entries.correction_calculator.CorrectionCalculator.graph_residual_error_per_species)


            * [`CorrectionCalculator.make_yaml()`](pymatgen.entries.md#pymatgen.entries.correction_calculator.CorrectionCalculator.make_yaml)


    * [pymatgen.entries.entry_tools module](pymatgen.entries.md#module-pymatgen.entries.entry_tools)


        * [`EntrySet`](pymatgen.entries.md#pymatgen.entries.entry_tools.EntrySet)


            * [`EntrySet._abc_impl`](pymatgen.entries.md#pymatgen.entries.entry_tools.EntrySet._abc_impl)


            * [`EntrySet.add()`](pymatgen.entries.md#pymatgen.entries.entry_tools.EntrySet.add)


            * [`EntrySet.as_dict()`](pymatgen.entries.md#pymatgen.entries.entry_tools.EntrySet.as_dict)


            * [`EntrySet.chemsys`](pymatgen.entries.md#pymatgen.entries.entry_tools.EntrySet.chemsys)


            * [`EntrySet.discard()`](pymatgen.entries.md#pymatgen.entries.entry_tools.EntrySet.discard)


            * [`EntrySet.from_csv()`](pymatgen.entries.md#pymatgen.entries.entry_tools.EntrySet.from_csv)


            * [`EntrySet.get_subset_in_chemsys()`](pymatgen.entries.md#pymatgen.entries.entry_tools.EntrySet.get_subset_in_chemsys)


            * [`EntrySet.ground_states`](pymatgen.entries.md#pymatgen.entries.entry_tools.EntrySet.ground_states)


            * [`EntrySet.is_ground_state()`](pymatgen.entries.md#pymatgen.entries.entry_tools.EntrySet.is_ground_state)


            * [`EntrySet.remove_non_ground_states()`](pymatgen.entries.md#pymatgen.entries.entry_tools.EntrySet.remove_non_ground_states)


            * [`EntrySet.to_csv()`](pymatgen.entries.md#pymatgen.entries.entry_tools.EntrySet.to_csv)


        * [`_get_host()`](pymatgen.entries.md#pymatgen.entries.entry_tools._get_host)


        * [`_perform_grouping()`](pymatgen.entries.md#pymatgen.entries.entry_tools._perform_grouping)


        * [`group_entries_by_composition()`](pymatgen.entries.md#pymatgen.entries.entry_tools.group_entries_by_composition)


        * [`group_entries_by_structure()`](pymatgen.entries.md#pymatgen.entries.entry_tools.group_entries_by_structure)


    * [pymatgen.entries.exp_entries module](pymatgen.entries.md#module-pymatgen.entries.exp_entries)


        * [`ExpEntry`](pymatgen.entries.md#pymatgen.entries.exp_entries.ExpEntry)


            * [`ExpEntry._abc_impl`](pymatgen.entries.md#pymatgen.entries.exp_entries.ExpEntry._abc_impl)


            * [`ExpEntry.as_dict()`](pymatgen.entries.md#pymatgen.entries.exp_entries.ExpEntry.as_dict)


            * [`ExpEntry.from_dict()`](pymatgen.entries.md#pymatgen.entries.exp_entries.ExpEntry.from_dict)


    * [pymatgen.entries.mixing_scheme module](pymatgen.entries.md#module-pymatgen.entries.mixing_scheme)


        * [`MaterialsProjectDFTMixingScheme`](pymatgen.entries.md#pymatgen.entries.mixing_scheme.MaterialsProjectDFTMixingScheme)


            * [`MaterialsProjectDFTMixingScheme._abc_impl`](pymatgen.entries.md#pymatgen.entries.mixing_scheme.MaterialsProjectDFTMixingScheme._abc_impl)


            * [`MaterialsProjectDFTMixingScheme._filter_and_sort_entries()`](pymatgen.entries.md#pymatgen.entries.mixing_scheme.MaterialsProjectDFTMixingScheme._filter_and_sort_entries)


            * [`MaterialsProjectDFTMixingScheme._populate_df_row()`](pymatgen.entries.md#pymatgen.entries.mixing_scheme.MaterialsProjectDFTMixingScheme._populate_df_row)


            * [`MaterialsProjectDFTMixingScheme.display_entries()`](pymatgen.entries.md#pymatgen.entries.mixing_scheme.MaterialsProjectDFTMixingScheme.display_entries)


            * [`MaterialsProjectDFTMixingScheme.get_adjustments()`](pymatgen.entries.md#pymatgen.entries.mixing_scheme.MaterialsProjectDFTMixingScheme.get_adjustments)


            * [`MaterialsProjectDFTMixingScheme.get_mixing_state_data()`](pymatgen.entries.md#pymatgen.entries.mixing_scheme.MaterialsProjectDFTMixingScheme.get_mixing_state_data)


            * [`MaterialsProjectDFTMixingScheme.process_entries()`](pymatgen.entries.md#pymatgen.entries.mixing_scheme.MaterialsProjectDFTMixingScheme.process_entries)


* [pymatgen.ext namespace](pymatgen.ext.md)




    * [pymatgen.ext.cod module](pymatgen.ext.md#module-pymatgen.ext.cod)


        * [`COD`](pymatgen.ext.md#pymatgen.ext.cod.COD)


            * [`COD.get_cod_ids()`](pymatgen.ext.md#pymatgen.ext.cod.COD.get_cod_ids)


            * [`COD.get_structure_by_formula()`](pymatgen.ext.md#pymatgen.ext.cod.COD.get_structure_by_formula)


            * [`COD.get_structure_by_id()`](pymatgen.ext.md#pymatgen.ext.cod.COD.get_structure_by_id)


            * [`COD.query()`](pymatgen.ext.md#pymatgen.ext.cod.COD.query)


            * [`COD.url`](pymatgen.ext.md#pymatgen.ext.cod.COD.url)


    * [pymatgen.ext.matproj module](pymatgen.ext.md#module-pymatgen.ext.matproj)


        * [`MPRestError`](pymatgen.ext.md#pymatgen.ext.matproj.MPRestError)


        * [`MPRester`](pymatgen.ext.md#pymatgen.ext.matproj.MPRester)


        * [`TaskType`](pymatgen.ext.md#pymatgen.ext.matproj.TaskType)


            * [`TaskType.GGAU_DEF`](pymatgen.ext.md#pymatgen.ext.matproj.TaskType.GGAU_DEF)


            * [`TaskType.GGAU_LINE`](pymatgen.ext.md#pymatgen.ext.matproj.TaskType.GGAU_LINE)


            * [`TaskType.GGAU_OPT`](pymatgen.ext.md#pymatgen.ext.matproj.TaskType.GGAU_OPT)


            * [`TaskType.GGAU_STATIC`](pymatgen.ext.md#pymatgen.ext.matproj.TaskType.GGAU_STATIC)


            * [`TaskType.GGAU_STATIC_DIEL`](pymatgen.ext.md#pymatgen.ext.matproj.TaskType.GGAU_STATIC_DIEL)


            * [`TaskType.GGAU_UNIFORM`](pymatgen.ext.md#pymatgen.ext.matproj.TaskType.GGAU_UNIFORM)


            * [`TaskType.GGA_DEF`](pymatgen.ext.md#pymatgen.ext.matproj.TaskType.GGA_DEF)


            * [`TaskType.GGA_LINE`](pymatgen.ext.md#pymatgen.ext.matproj.TaskType.GGA_LINE)


            * [`TaskType.GGA_OPT`](pymatgen.ext.md#pymatgen.ext.matproj.TaskType.GGA_OPT)


            * [`TaskType.GGA_STATIC`](pymatgen.ext.md#pymatgen.ext.matproj.TaskType.GGA_STATIC)


            * [`TaskType.GGA_STATIC_DIEL`](pymatgen.ext.md#pymatgen.ext.matproj.TaskType.GGA_STATIC_DIEL)


            * [`TaskType.GGA_UNIFORM`](pymatgen.ext.md#pymatgen.ext.matproj.TaskType.GGA_UNIFORM)


            * [`TaskType.LDA_STATIC_DIEL`](pymatgen.ext.md#pymatgen.ext.matproj.TaskType.LDA_STATIC_DIEL)


            * [`TaskType.SCAN_OPT`](pymatgen.ext.md#pymatgen.ext.matproj.TaskType.SCAN_OPT)


        * [`_MPResterLegacy`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy)


            * [`_MPResterLegacy._check_get_download_info_url_by_task_id()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy._check_get_download_info_url_by_task_id)


            * [`_MPResterLegacy._check_nomad_exist()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy._check_nomad_exist)


            * [`_MPResterLegacy._make_request()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy._make_request)


            * [`_MPResterLegacy._print_help_message()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy._print_help_message)


            * [`_MPResterLegacy.delete_snl()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.delete_snl)


            * [`_MPResterLegacy.find_structure()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.find_structure)


            * [`_MPResterLegacy.get_all_substrates()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_all_substrates)


            * [`_MPResterLegacy.get_bandstructure_by_material_id()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_bandstructure_by_material_id)


            * [`_MPResterLegacy.get_cohesive_energy()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_cohesive_energy)


            * [`_MPResterLegacy.get_data()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_data)


            * [`_MPResterLegacy.get_database_version()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_database_version)


            * [`_MPResterLegacy.get_doc()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_doc)


            * [`_MPResterLegacy.get_dos_by_material_id()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_dos_by_material_id)


            * [`_MPResterLegacy.get_download_info()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_download_info)


            * [`_MPResterLegacy.get_entries()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_entries)


            * [`_MPResterLegacy.get_entries_in_chemsys()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_entries_in_chemsys)


            * [`_MPResterLegacy.get_entry_by_material_id()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_entry_by_material_id)


            * [`_MPResterLegacy.get_exp_entry()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_exp_entry)


            * [`_MPResterLegacy.get_exp_thermo_data()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_exp_thermo_data)


            * [`_MPResterLegacy.get_gb_data()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_gb_data)


            * [`_MPResterLegacy.get_interface_reactions()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_interface_reactions)


            * [`_MPResterLegacy.get_material_id()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_material_id)


            * [`_MPResterLegacy.get_materials_id_from_task_id()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_materials_id_from_task_id)


            * [`_MPResterLegacy.get_materials_id_references()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_materials_id_references)


            * [`_MPResterLegacy.get_materials_ids()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_materials_ids)


            * [`_MPResterLegacy.get_phonon_bandstructure_by_material_id()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_phonon_bandstructure_by_material_id)


            * [`_MPResterLegacy.get_phonon_ddb_by_material_id()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_phonon_ddb_by_material_id)


            * [`_MPResterLegacy.get_phonon_dos_by_material_id()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_phonon_dos_by_material_id)


            * [`_MPResterLegacy.get_pourbaix_entries()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_pourbaix_entries)


            * [`_MPResterLegacy.get_reaction()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_reaction)


            * [`_MPResterLegacy.get_stability()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_stability)


            * [`_MPResterLegacy.get_structure_by_material_id()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_structure_by_material_id)


            * [`_MPResterLegacy.get_structures()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_structures)


            * [`_MPResterLegacy.get_substrates()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_substrates)


            * [`_MPResterLegacy.get_surface_data()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_surface_data)


            * [`_MPResterLegacy.get_task_data()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_task_data)


            * [`_MPResterLegacy.get_wulff_shape()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_wulff_shape)


            * [`_MPResterLegacy.get_xas_data()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.get_xas_data)


            * [`_MPResterLegacy.parse_criteria()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.parse_criteria)


            * [`_MPResterLegacy.query()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.query)


            * [`_MPResterLegacy.query_snl()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.query_snl)


            * [`_MPResterLegacy.submit_snl()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.submit_snl)


            * [`_MPResterLegacy.submit_structures()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.submit_structures)


            * [`_MPResterLegacy.submit_vasp_directory()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.submit_vasp_directory)


            * [`_MPResterLegacy.supported_properties`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.supported_properties)


            * [`_MPResterLegacy.supported_task_properties`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterLegacy.supported_task_properties)


        * [`_MPResterNewBasic`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterNewBasic)


            * [`_MPResterNewBasic.get_doc()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterNewBasic.get_doc)


            * [`_MPResterNewBasic.get_entries()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterNewBasic.get_entries)


            * [`_MPResterNewBasic.get_entries_in_chemsys()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterNewBasic.get_entries_in_chemsys)


            * [`_MPResterNewBasic.get_entry_by_material_id()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterNewBasic.get_entry_by_material_id)


            * [`_MPResterNewBasic.get_initial_structures_by_material_id()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterNewBasic.get_initial_structures_by_material_id)


            * [`_MPResterNewBasic.get_material_ids()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterNewBasic.get_material_ids)


            * [`_MPResterNewBasic.get_materials_ids()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterNewBasic.get_materials_ids)


            * [`_MPResterNewBasic.get_structure_by_material_id()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterNewBasic.get_structure_by_material_id)


            * [`_MPResterNewBasic.get_structures()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterNewBasic.get_structures)


            * [`_MPResterNewBasic.get_summary()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterNewBasic.get_summary)


            * [`_MPResterNewBasic.get_summary_by_material_id()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterNewBasic.get_summary_by_material_id)


            * [`_MPResterNewBasic.request()`](pymatgen.ext.md#pymatgen.ext.matproj._MPResterNewBasic.request)


        * [`get_chunks()`](pymatgen.ext.md#pymatgen.ext.matproj.get_chunks)


    * [pymatgen.ext.optimade module](pymatgen.ext.md#module-pymatgen.ext.optimade)


        * [`OptimadeRester`](pymatgen.ext.md#pymatgen.ext.optimade.OptimadeRester)


            * [`OptimadeRester._build_filter()`](pymatgen.ext.md#pymatgen.ext.optimade.OptimadeRester._build_filter)


            * [`OptimadeRester._get_json()`](pymatgen.ext.md#pymatgen.ext.optimade.OptimadeRester._get_json)


            * [`OptimadeRester._get_snls_from_resource()`](pymatgen.ext.md#pymatgen.ext.optimade.OptimadeRester._get_snls_from_resource)


            * [`OptimadeRester._handle_response_fields()`](pymatgen.ext.md#pymatgen.ext.optimade.OptimadeRester._handle_response_fields)


            * [`OptimadeRester._parse_provider()`](pymatgen.ext.md#pymatgen.ext.optimade.OptimadeRester._parse_provider)


            * [`OptimadeRester._validate_provider()`](pymatgen.ext.md#pymatgen.ext.optimade.OptimadeRester._validate_provider)


            * [`OptimadeRester.aliases`](pymatgen.ext.md#pymatgen.ext.optimade.OptimadeRester.aliases)


            * [`OptimadeRester.describe()`](pymatgen.ext.md#pymatgen.ext.optimade.OptimadeRester.describe)


            * [`OptimadeRester.get_snls()`](pymatgen.ext.md#pymatgen.ext.optimade.OptimadeRester.get_snls)


            * [`OptimadeRester.get_snls_with_filter()`](pymatgen.ext.md#pymatgen.ext.optimade.OptimadeRester.get_snls_with_filter)


            * [`OptimadeRester.get_structures()`](pymatgen.ext.md#pymatgen.ext.optimade.OptimadeRester.get_structures)


            * [`OptimadeRester.get_structures_with_filter()`](pymatgen.ext.md#pymatgen.ext.optimade.OptimadeRester.get_structures_with_filter)


            * [`OptimadeRester.mandatory_response_fields`](pymatgen.ext.md#pymatgen.ext.optimade.OptimadeRester.mandatory_response_fields)


            * [`OptimadeRester.refresh_aliases()`](pymatgen.ext.md#pymatgen.ext.optimade.OptimadeRester.refresh_aliases)


        * [`Provider`](pymatgen.ext.md#pymatgen.ext.optimade.Provider)


            * [`Provider._asdict()`](pymatgen.ext.md#pymatgen.ext.optimade.Provider._asdict)


            * [`Provider._field_defaults`](pymatgen.ext.md#pymatgen.ext.optimade.Provider._field_defaults)


            * [`Provider._fields`](pymatgen.ext.md#pymatgen.ext.optimade.Provider._fields)


            * [`Provider._make()`](pymatgen.ext.md#pymatgen.ext.optimade.Provider._make)


            * [`Provider._replace()`](pymatgen.ext.md#pymatgen.ext.optimade.Provider._replace)


            * [`Provider.base_url`](pymatgen.ext.md#pymatgen.ext.optimade.Provider.base_url)


            * [`Provider.description`](pymatgen.ext.md#pymatgen.ext.optimade.Provider.description)


            * [`Provider.homepage`](pymatgen.ext.md#pymatgen.ext.optimade.Provider.homepage)


            * [`Provider.name`](pymatgen.ext.md#pymatgen.ext.optimade.Provider.name)


            * [`Provider.prefix`](pymatgen.ext.md#pymatgen.ext.optimade.Provider.prefix)


* [pymatgen.io namespace](pymatgen.io.md)


    * [Subpackages](pymatgen.io.md#subpackages)


        * [pymatgen.io.abinit package](pymatgen.io.abinit.md)




            * [pymatgen.io.abinit.abiobjects module](pymatgen.io.abinit.md#module-pymatgen.io.abinit.abiobjects)


                * [`AbivarAble`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.AbivarAble)


                    * [`AbivarAble._abc_impl`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.AbivarAble._abc_impl)


                    * [`AbivarAble.to_abivars()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.AbivarAble.to_abivars)


                * [`Constraints`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.Constraints)


                    * [`Constraints._abc_impl`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.Constraints._abc_impl)


                    * [`Constraints.to_abivars()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.Constraints.to_abivars)


                * [`Electrons`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.Electrons)


                    * [`Electrons._abc_impl`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.Electrons._abc_impl)


                    * [`Electrons.as_dict()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.Electrons.as_dict)


                    * [`Electrons.from_dict()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.Electrons.from_dict)


                    * [`Electrons.nspden`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.Electrons.nspden)


                    * [`Electrons.nspinor`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.Electrons.nspinor)


                    * [`Electrons.nsppol`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.Electrons.nsppol)


                    * [`Electrons.to_abivars()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.Electrons.to_abivars)


                * [`ElectronsAlgorithm`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.ElectronsAlgorithm)


                    * [`ElectronsAlgorithm._DEFAULT`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.ElectronsAlgorithm._DEFAULT)


                    * [`ElectronsAlgorithm._abc_impl`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.ElectronsAlgorithm._abc_impl)


                    * [`ElectronsAlgorithm.as_dict()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.ElectronsAlgorithm.as_dict)


                    * [`ElectronsAlgorithm.from_dict()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.ElectronsAlgorithm.from_dict)


                    * [`ElectronsAlgorithm.to_abivars()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.ElectronsAlgorithm.to_abivars)


                * [`ExcHamiltonian`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.ExcHamiltonian)


                    * [`ExcHamiltonian._ALGO2VAR`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.ExcHamiltonian._ALGO2VAR)


                    * [`ExcHamiltonian._COULOMB_MODES`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.ExcHamiltonian._COULOMB_MODES)


                    * [`ExcHamiltonian._EXC_TYPES`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.ExcHamiltonian._EXC_TYPES)


                    * [`ExcHamiltonian._abc_impl`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.ExcHamiltonian._abc_impl)


                    * [`ExcHamiltonian.inclvkb`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.ExcHamiltonian.inclvkb)


                    * [`ExcHamiltonian.to_abivars()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.ExcHamiltonian.to_abivars)


                    * [`ExcHamiltonian.use_cg`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.ExcHamiltonian.use_cg)


                    * [`ExcHamiltonian.use_direct_diago`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.ExcHamiltonian.use_direct_diago)


                    * [`ExcHamiltonian.use_haydock`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.ExcHamiltonian.use_haydock)


                * [`HilbertTransform`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.HilbertTransform)


                    * [`HilbertTransform._abc_impl`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.HilbertTransform._abc_impl)


                    * [`HilbertTransform.to_abivars()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.HilbertTransform.to_abivars)


                * [`KSampling`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.KSampling)


                    * [`KSampling._abc_impl`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.KSampling._abc_impl)


                    * [`KSampling._path()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.KSampling._path)


                    * [`KSampling.as_dict()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.KSampling.as_dict)


                    * [`KSampling.automatic_density()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.KSampling.automatic_density)


                    * [`KSampling.explicit_path()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.KSampling.explicit_path)


                    * [`KSampling.from_dict()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.KSampling.from_dict)


                    * [`KSampling.gamma_centered()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.KSampling.gamma_centered)


                    * [`KSampling.gamma_only()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.KSampling.gamma_only)


                    * [`KSampling.is_homogeneous`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.KSampling.is_homogeneous)


                    * [`KSampling.monkhorst()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.KSampling.monkhorst)


                    * [`KSampling.monkhorst_automatic()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.KSampling.monkhorst_automatic)


                    * [`KSampling.path_from_structure()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.KSampling.path_from_structure)


                    * [`KSampling.to_abivars()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.KSampling.to_abivars)


                * [`KSamplingModes`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.KSamplingModes)


                    * [`KSamplingModes.automatic`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.KSamplingModes.automatic)


                    * [`KSamplingModes.monkhorst`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.KSamplingModes.monkhorst)


                    * [`KSamplingModes.path`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.KSamplingModes.path)


                * [`ModelDielectricFunction`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.ModelDielectricFunction)


                    * [`ModelDielectricFunction._abc_impl`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.ModelDielectricFunction._abc_impl)


                    * [`ModelDielectricFunction.to_abivars()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.ModelDielectricFunction.to_abivars)


                * [`PPModel`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.PPModel)


                    * [`PPModel._abc_impl`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.PPModel._abc_impl)


                    * [`PPModel.as_dict()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.PPModel.as_dict)


                    * [`PPModel.as_ppmodel()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.PPModel.as_ppmodel)


                    * [`PPModel.from_dict()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.PPModel.from_dict)


                    * [`PPModel.get_noppmodel()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.PPModel.get_noppmodel)


                    * [`PPModel.to_abivars()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.PPModel.to_abivars)


                * [`PPModelModes`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.PPModelModes)


                    * [`PPModelModes.farid`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.PPModelModes.farid)


                    * [`PPModelModes.godby`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.PPModelModes.godby)


                    * [`PPModelModes.hybersten`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.PPModelModes.hybersten)


                    * [`PPModelModes.linden`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.PPModelModes.linden)


                    * [`PPModelModes.noppmodel`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.PPModelModes.noppmodel)


                * [`RelaxationMethod`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.RelaxationMethod)


                    * [`RelaxationMethod.IONMOV_DEFAULT`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.RelaxationMethod.IONMOV_DEFAULT)


                    * [`RelaxationMethod.OPTCELL_DEFAULT`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.RelaxationMethod.OPTCELL_DEFAULT)


                    * [`RelaxationMethod._abc_impl`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.RelaxationMethod._abc_impl)


                    * [`RelaxationMethod._default_vars`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.RelaxationMethod._default_vars)


                    * [`RelaxationMethod.as_dict()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.RelaxationMethod.as_dict)


                    * [`RelaxationMethod.atoms_and_cell()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.RelaxationMethod.atoms_and_cell)


                    * [`RelaxationMethod.atoms_only()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.RelaxationMethod.atoms_only)


                    * [`RelaxationMethod.from_dict()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.RelaxationMethod.from_dict)


                    * [`RelaxationMethod.move_atoms`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.RelaxationMethod.move_atoms)


                    * [`RelaxationMethod.move_cell`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.RelaxationMethod.move_cell)


                    * [`RelaxationMethod.to_abivars()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.RelaxationMethod.to_abivars)


                * [`Screening`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.Screening)


                    * [`Screening._SC_MODES`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.Screening._SC_MODES)


                    * [`Screening._WTYPES`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.Screening._WTYPES)


                    * [`Screening._abc_impl`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.Screening._abc_impl)


                    * [`Screening.to_abivars()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.Screening.to_abivars)


                    * [`Screening.use_hilbert`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.Screening.use_hilbert)


                * [`SelfEnergy`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.SelfEnergy)


                    * [`SelfEnergy._SC_MODES`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.SelfEnergy._SC_MODES)


                    * [`SelfEnergy._SIGMA_TYPES`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.SelfEnergy._SIGMA_TYPES)


                    * [`SelfEnergy._abc_impl`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.SelfEnergy._abc_impl)


                    * [`SelfEnergy.gwcalctyp`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.SelfEnergy.gwcalctyp)


                    * [`SelfEnergy.symsigma`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.SelfEnergy.symsigma)


                    * [`SelfEnergy.to_abivars()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.SelfEnergy.to_abivars)


                    * [`SelfEnergy.use_ppmodel`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.SelfEnergy.use_ppmodel)


                * [`Smearing`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.Smearing)


                    * [`Smearing._abc_impl`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.Smearing._abc_impl)


                    * [`Smearing._mode2occopt`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.Smearing._mode2occopt)


                    * [`Smearing.as_dict()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.Smearing.as_dict)


                    * [`Smearing.as_smearing()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.Smearing.as_smearing)


                    * [`Smearing.from_dict()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.Smearing.from_dict)


                    * [`Smearing.mode`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.Smearing.mode)


                    * [`Smearing.nosmearing()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.Smearing.nosmearing)


                    * [`Smearing.to_abivars()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.Smearing.to_abivars)


                * [`SpinMode`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.SpinMode)


                    * [`SpinMode._abc_impl`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.SpinMode._abc_impl)


                    * [`SpinMode.as_dict()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.SpinMode.as_dict)


                    * [`SpinMode.as_spinmode()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.SpinMode.as_spinmode)


                    * [`SpinMode.from_dict()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.SpinMode.from_dict)


                    * [`SpinMode.to_abivars()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.SpinMode.to_abivars)


                * [`contract()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.contract)


                * [`lattice_from_abivars()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.lattice_from_abivars)


                * [`species_by_znucl()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.species_by_znucl)


                * [`structure_from_abivars()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.structure_from_abivars)


                * [`structure_to_abivars()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abiobjects.structure_to_abivars)


            * [pymatgen.io.abinit.abitimer module](pymatgen.io.abinit.md#module-pymatgen.io.abinit.abitimer)


                * [`AbinitTimer`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimer)


                    * [`AbinitTimer._reduce_sections()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimer._reduce_sections)


                    * [`AbinitTimer.cpuwall_histogram()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimer.cpuwall_histogram)


                    * [`AbinitTimer.get_dataframe()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimer.get_dataframe)


                    * [`AbinitTimer.get_section()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimer.get_section)


                    * [`AbinitTimer.get_values()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimer.get_values)


                    * [`AbinitTimer.names_and_values()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimer.names_and_values)


                    * [`AbinitTimer.ncpus`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimer.ncpus)


                    * [`AbinitTimer.order_sections()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimer.order_sections)


                    * [`AbinitTimer.pie()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimer.pie)


                    * [`AbinitTimer.scatter_hist()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimer.scatter_hist)


                    * [`AbinitTimer.sum_sections()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimer.sum_sections)


                    * [`AbinitTimer.to_csv()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimer.to_csv)


                    * [`AbinitTimer.to_table()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimer.to_table)


                    * [`AbinitTimer.totable()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimer.totable)


                * [`AbinitTimerParseError`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimerParseError)


                * [`AbinitTimerParser`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimerParser)


                    * [`AbinitTimerParser.BEGIN_TAG`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimerParser.BEGIN_TAG)


                    * [`AbinitTimerParser.END_TAG`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimerParser.END_TAG)


                    * [`AbinitTimerParser.Error`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimerParser.Error)


                    * [`AbinitTimerParser._abc_impl`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimerParser._abc_impl)


                    * [`AbinitTimerParser._read()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimerParser._read)


                    * [`AbinitTimerParser.filenames`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimerParser.filenames)


                    * [`AbinitTimerParser.get_sections()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimerParser.get_sections)


                    * [`AbinitTimerParser.parse()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimerParser.parse)


                    * [`AbinitTimerParser.pefficiency()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimerParser.pefficiency)


                    * [`AbinitTimerParser.plot_all()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimerParser.plot_all)


                    * [`AbinitTimerParser.plot_efficiency()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimerParser.plot_efficiency)


                    * [`AbinitTimerParser.plot_pie()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimerParser.plot_pie)


                    * [`AbinitTimerParser.plot_stacked_hist()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimerParser.plot_stacked_hist)


                    * [`AbinitTimerParser.section_names()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimerParser.section_names)


                    * [`AbinitTimerParser.summarize()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimerParser.summarize)


                    * [`AbinitTimerParser.timers()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimerParser.timers)


                    * [`AbinitTimerParser.walk()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimerParser.walk)


                * [`AbinitTimerSection`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimerSection)


                    * [`AbinitTimerSection.FIELDS`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimerSection.FIELDS)


                    * [`AbinitTimerSection.NUMERIC_FIELDS`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimerSection.NUMERIC_FIELDS)


                    * [`AbinitTimerSection.STR_FIELDS`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimerSection.STR_FIELDS)


                    * [`AbinitTimerSection.fake()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimerSection.fake)


                    * [`AbinitTimerSection.to_csvline()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimerSection.to_csvline)


                    * [`AbinitTimerSection.to_dict()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimerSection.to_dict)


                    * [`AbinitTimerSection.to_tuple()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.AbinitTimerSection.to_tuple)


                * [`ParallelEfficiency`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.ParallelEfficiency)


                    * [`ParallelEfficiency._order_by_peff()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.ParallelEfficiency._order_by_peff)


                    * [`ParallelEfficiency.bad_sections()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.ParallelEfficiency.bad_sections)


                    * [`ParallelEfficiency.good_sections()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.ParallelEfficiency.good_sections)


                    * [`ParallelEfficiency.totable()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.ParallelEfficiency.totable)


                * [`alternate()`](pymatgen.io.abinit.md#pymatgen.io.abinit.abitimer.alternate)


            * [pymatgen.io.abinit.inputs module](pymatgen.io.abinit.md#module-pymatgen.io.abinit.inputs)


                * [`AbstractInput`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.AbstractInput)


                    * [`AbstractInput._abc_impl`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.AbstractInput._abc_impl)


                    * [`AbstractInput._check_varname()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.AbstractInput._check_varname)


                    * [`AbstractInput.deepcopy()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.AbstractInput.deepcopy)


                    * [`AbstractInput.pop_vars()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.AbstractInput.pop_vars)


                    * [`AbstractInput.remove_vars()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.AbstractInput.remove_vars)


                    * [`AbstractInput.set_vars()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.AbstractInput.set_vars)


                    * [`AbstractInput.set_vars_ifnotin()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.AbstractInput.set_vars_ifnotin)


                    * [`AbstractInput.to_str()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.AbstractInput.to_str)


                    * [`AbstractInput.vars`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.AbstractInput.vars)


                    * [`AbstractInput.write()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.AbstractInput.write)


                * [`BasicAbinitInput`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicAbinitInput)


                    * [`BasicAbinitInput.Error`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicAbinitInput.Error)


                    * [`BasicAbinitInput._abc_impl`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicAbinitInput._abc_impl)


                    * [`BasicAbinitInput._check_varname()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicAbinitInput._check_varname)


                    * [`BasicAbinitInput.add_abiobjects()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicAbinitInput.add_abiobjects)


                    * [`BasicAbinitInput.as_dict()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicAbinitInput.as_dict)


                    * [`BasicAbinitInput.comment`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicAbinitInput.comment)


                    * [`BasicAbinitInput.from_dict()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicAbinitInput.from_dict)


                    * [`BasicAbinitInput.isnc`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicAbinitInput.isnc)


                    * [`BasicAbinitInput.ispaw`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicAbinitInput.ispaw)


                    * [`BasicAbinitInput.new_with_vars()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicAbinitInput.new_with_vars)


                    * [`BasicAbinitInput.pop_irdvars()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicAbinitInput.pop_irdvars)


                    * [`BasicAbinitInput.pop_tolerances()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicAbinitInput.pop_tolerances)


                    * [`BasicAbinitInput.pseudos`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicAbinitInput.pseudos)


                    * [`BasicAbinitInput.set_comment()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicAbinitInput.set_comment)


                    * [`BasicAbinitInput.set_gamma_sampling()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicAbinitInput.set_gamma_sampling)


                    * [`BasicAbinitInput.set_kmesh()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicAbinitInput.set_kmesh)


                    * [`BasicAbinitInput.set_kpath()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicAbinitInput.set_kpath)


                    * [`BasicAbinitInput.set_spin_mode()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicAbinitInput.set_spin_mode)


                    * [`BasicAbinitInput.set_structure()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicAbinitInput.set_structure)


                    * [`BasicAbinitInput.structure`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicAbinitInput.structure)


                    * [`BasicAbinitInput.to_str()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicAbinitInput.to_str)


                    * [`BasicAbinitInput.to_string()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicAbinitInput.to_string)


                    * [`BasicAbinitInput.vars`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicAbinitInput.vars)


                * [`BasicAbinitInputError`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicAbinitInputError)


                * [`BasicMultiDataset`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicMultiDataset)


                    * [`BasicMultiDataset.Error`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicMultiDataset.Error)


                    * [`BasicMultiDataset.addnew_from()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicMultiDataset.addnew_from)


                    * [`BasicMultiDataset.append()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicMultiDataset.append)


                    * [`BasicMultiDataset.deepcopy()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicMultiDataset.deepcopy)


                    * [`BasicMultiDataset.extend()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicMultiDataset.extend)


                    * [`BasicMultiDataset.from_inputs()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicMultiDataset.from_inputs)


                    * [`BasicMultiDataset.has_same_structures`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicMultiDataset.has_same_structures)


                    * [`BasicMultiDataset.isnc`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicMultiDataset.isnc)


                    * [`BasicMultiDataset.ispaw`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicMultiDataset.ispaw)


                    * [`BasicMultiDataset.ndtset`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicMultiDataset.ndtset)


                    * [`BasicMultiDataset.pseudos`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicMultiDataset.pseudos)


                    * [`BasicMultiDataset.replicate_input()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicMultiDataset.replicate_input)


                    * [`BasicMultiDataset.split_datasets()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicMultiDataset.split_datasets)


                    * [`BasicMultiDataset.to_str()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicMultiDataset.to_str)


                    * [`BasicMultiDataset.to_string()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicMultiDataset.to_string)


                    * [`BasicMultiDataset.write()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.BasicMultiDataset.write)


                * [`ShiftMode`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.ShiftMode)


                    * [`ShiftMode.GammaCentered`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.ShiftMode.GammaCentered)


                    * [`ShiftMode.MonkhorstPack`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.ShiftMode.MonkhorstPack)


                    * [`ShiftMode.OneSymmetric`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.ShiftMode.OneSymmetric)


                    * [`ShiftMode.Symmetric`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.ShiftMode.Symmetric)


                    * [`ShiftMode.from_object()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.ShiftMode.from_object)


                * [`_find_ecut_pawecutdg()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs._find_ecut_pawecutdg)


                * [`_find_scf_nband()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs._find_scf_nband)


                * [`_get_shifts()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs._get_shifts)


                * [`_stopping_criterion()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs._stopping_criterion)


                * [`as_structure()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.as_structure)


                * [`calc_shiftk()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.calc_shiftk)


                * [`ebands_input()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.ebands_input)


                * [`gs_input()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.gs_input)


                * [`ion_ioncell_relax_input()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.ion_ioncell_relax_input)


                * [`num_valence_electrons()`](pymatgen.io.abinit.md#pymatgen.io.abinit.inputs.num_valence_electrons)


            * [pymatgen.io.abinit.netcdf module](pymatgen.io.abinit.md#module-pymatgen.io.abinit.netcdf)


                * [`AbinitHeader`](pymatgen.io.abinit.md#pymatgen.io.abinit.netcdf.AbinitHeader)


                    * [`AbinitHeader.to_str()`](pymatgen.io.abinit.md#pymatgen.io.abinit.netcdf.AbinitHeader.to_str)


                    * [`AbinitHeader.to_string()`](pymatgen.io.abinit.md#pymatgen.io.abinit.netcdf.AbinitHeader.to_string)


                * [`ETSF_Reader`](pymatgen.io.abinit.md#pymatgen.io.abinit.netcdf.ETSF_Reader)


                    * [`ETSF_Reader.chemical_symbols()`](pymatgen.io.abinit.md#pymatgen.io.abinit.netcdf.ETSF_Reader.chemical_symbols)


                    * [`ETSF_Reader.read_abinit_hdr()`](pymatgen.io.abinit.md#pymatgen.io.abinit.netcdf.ETSF_Reader.read_abinit_hdr)


                    * [`ETSF_Reader.read_abinit_xcfunc()`](pymatgen.io.abinit.md#pymatgen.io.abinit.netcdf.ETSF_Reader.read_abinit_xcfunc)


                    * [`ETSF_Reader.read_structure()`](pymatgen.io.abinit.md#pymatgen.io.abinit.netcdf.ETSF_Reader.read_structure)


                    * [`ETSF_Reader.typeidx_from_symbol()`](pymatgen.io.abinit.md#pymatgen.io.abinit.netcdf.ETSF_Reader.typeidx_from_symbol)


                * [`NO_DEFAULT`](pymatgen.io.abinit.md#pymatgen.io.abinit.netcdf.NO_DEFAULT)


                * [`NetcdfReader`](pymatgen.io.abinit.md#pymatgen.io.abinit.netcdf.NetcdfReader)


                    * [`NetcdfReader.Error`](pymatgen.io.abinit.md#pymatgen.io.abinit.netcdf.NetcdfReader.Error)


                    * [`NetcdfReader._read_dimensions()`](pymatgen.io.abinit.md#pymatgen.io.abinit.netcdf.NetcdfReader._read_dimensions)


                    * [`NetcdfReader._read_variables()`](pymatgen.io.abinit.md#pymatgen.io.abinit.netcdf.NetcdfReader._read_variables)


                    * [`NetcdfReader.close()`](pymatgen.io.abinit.md#pymatgen.io.abinit.netcdf.NetcdfReader.close)


                    * [`NetcdfReader.print_tree()`](pymatgen.io.abinit.md#pymatgen.io.abinit.netcdf.NetcdfReader.print_tree)


                    * [`NetcdfReader.read_dimvalue()`](pymatgen.io.abinit.md#pymatgen.io.abinit.netcdf.NetcdfReader.read_dimvalue)


                    * [`NetcdfReader.read_keys()`](pymatgen.io.abinit.md#pymatgen.io.abinit.netcdf.NetcdfReader.read_keys)


                    * [`NetcdfReader.read_value()`](pymatgen.io.abinit.md#pymatgen.io.abinit.netcdf.NetcdfReader.read_value)


                    * [`NetcdfReader.read_variable()`](pymatgen.io.abinit.md#pymatgen.io.abinit.netcdf.NetcdfReader.read_variable)


                    * [`NetcdfReader.read_varnames()`](pymatgen.io.abinit.md#pymatgen.io.abinit.netcdf.NetcdfReader.read_varnames)


                    * [`NetcdfReader.walk_tree()`](pymatgen.io.abinit.md#pymatgen.io.abinit.netcdf.NetcdfReader.walk_tree)


                * [`NetcdfReaderError`](pymatgen.io.abinit.md#pymatgen.io.abinit.netcdf.NetcdfReaderError)


                * [`_H`](pymatgen.io.abinit.md#pymatgen.io.abinit.netcdf._H)


                    * [`_H.doc`](pymatgen.io.abinit.md#pymatgen.io.abinit.netcdf._H.doc)


                    * [`_H.etsf_name`](pymatgen.io.abinit.md#pymatgen.io.abinit.netcdf._H.etsf_name)


                    * [`_H.name`](pymatgen.io.abinit.md#pymatgen.io.abinit.netcdf._H.name)


                * [`_asreader()`](pymatgen.io.abinit.md#pymatgen.io.abinit.netcdf._asreader)


                * [`as_etsfreader()`](pymatgen.io.abinit.md#pymatgen.io.abinit.netcdf.as_etsfreader)


                * [`as_ncreader()`](pymatgen.io.abinit.md#pymatgen.io.abinit.netcdf.as_ncreader)


                * [`structure_from_ncdata()`](pymatgen.io.abinit.md#pymatgen.io.abinit.netcdf.structure_from_ncdata)


            * [pymatgen.io.abinit.pseudos module](pymatgen.io.abinit.md#module-pymatgen.io.abinit.pseudos)


                * [`AbinitHeader`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.AbinitHeader)


                * [`AbinitPseudo`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.AbinitPseudo)


                    * [`AbinitPseudo.Z`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.AbinitPseudo.Z)


                    * [`AbinitPseudo.Z_val`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.AbinitPseudo.Z_val)


                    * [`AbinitPseudo._abc_impl`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.AbinitPseudo._abc_impl)


                    * [`AbinitPseudo.l_local`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.AbinitPseudo.l_local)


                    * [`AbinitPseudo.l_max`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.AbinitPseudo.l_max)


                    * [`AbinitPseudo.summary`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.AbinitPseudo.summary)


                    * [`AbinitPseudo.supports_soc`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.AbinitPseudo.supports_soc)


                * [`Hint`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Hint)


                    * [`Hint.as_dict()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Hint.as_dict)


                    * [`Hint.from_dict()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Hint.from_dict)


                * [`NcAbinitHeader`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.NcAbinitHeader)


                    * [`NcAbinitHeader._VARS`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.NcAbinitHeader._VARS)


                    * [`NcAbinitHeader.fhi_header()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.NcAbinitHeader.fhi_header)


                    * [`NcAbinitHeader.gth_header()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.NcAbinitHeader.gth_header)


                    * [`NcAbinitHeader.hgh_header()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.NcAbinitHeader.hgh_header)


                    * [`NcAbinitHeader.oncvpsp_header()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.NcAbinitHeader.oncvpsp_header)


                    * [`NcAbinitHeader.tm_header()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.NcAbinitHeader.tm_header)


                * [`NcAbinitPseudo`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.NcAbinitPseudo)


                    * [`NcAbinitPseudo.Z`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.NcAbinitPseudo.Z)


                    * [`NcAbinitPseudo.Z_val`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.NcAbinitPseudo.Z_val)


                    * [`NcAbinitPseudo._abc_impl`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.NcAbinitPseudo._abc_impl)


                    * [`NcAbinitPseudo.l_local`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.NcAbinitPseudo.l_local)


                    * [`NcAbinitPseudo.l_max`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.NcAbinitPseudo.l_max)


                    * [`NcAbinitPseudo.nlcc_radius`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.NcAbinitPseudo.nlcc_radius)


                    * [`NcAbinitPseudo.summary`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.NcAbinitPseudo.summary)


                * [`NcPseudo`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.NcPseudo)


                    * [`NcPseudo._abc_impl`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.NcPseudo._abc_impl)


                    * [`NcPseudo.has_nlcc`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.NcPseudo.has_nlcc)


                    * [`NcPseudo.nlcc_radius`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.NcPseudo.nlcc_radius)


                    * [`NcPseudo.rcore`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.NcPseudo.rcore)


                * [`PawAbinitHeader`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawAbinitHeader)


                    * [`PawAbinitHeader._VARS`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawAbinitHeader._VARS)


                    * [`PawAbinitHeader.paw_header()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawAbinitHeader.paw_header)


                * [`PawAbinitPseudo`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawAbinitPseudo)


                    * [`PawAbinitPseudo._abc_impl`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawAbinitPseudo._abc_impl)


                    * [`PawAbinitPseudo.paw_radius`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawAbinitPseudo.paw_radius)


                    * [`PawAbinitPseudo.supports_soc`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawAbinitPseudo.supports_soc)


                * [`PawPseudo`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawPseudo)


                    * [`PawPseudo._abc_impl`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawPseudo._abc_impl)


                    * [`PawPseudo.paw_radius`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawPseudo.paw_radius)


                    * [`PawPseudo.rcore`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawPseudo.rcore)


                * [`PawXmlSetup`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawXmlSetup)


                    * [`PawXmlSetup.Z`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawXmlSetup.Z)


                    * [`PawXmlSetup.Z_val`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawXmlSetup.Z_val)


                    * [`PawXmlSetup._abc_impl`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawXmlSetup._abc_impl)


                    * [`PawXmlSetup._eval_grid()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawXmlSetup._eval_grid)


                    * [`PawXmlSetup._parse_all_radfuncs()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawXmlSetup._parse_all_radfuncs)


                    * [`PawXmlSetup._parse_radfunc()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawXmlSetup._parse_radfunc)


                    * [`PawXmlSetup.ae_core_density()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawXmlSetup.ae_core_density)


                    * [`PawXmlSetup.ae_partial_waves()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawXmlSetup.ae_partial_waves)


                    * [`PawXmlSetup.l_local`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawXmlSetup.l_local)


                    * [`PawXmlSetup.l_max`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawXmlSetup.l_max)


                    * [`PawXmlSetup.paw_radius`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawXmlSetup.paw_radius)


                    * [`PawXmlSetup.plot_densities()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawXmlSetup.plot_densities)


                    * [`PawXmlSetup.plot_projectors()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawXmlSetup.plot_projectors)


                    * [`PawXmlSetup.plot_waves()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawXmlSetup.plot_waves)


                    * [`PawXmlSetup.projector_functions()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawXmlSetup.projector_functions)


                    * [`PawXmlSetup.pseudo_core_density()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawXmlSetup.pseudo_core_density)


                    * [`PawXmlSetup.pseudo_partial_waves`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawXmlSetup.pseudo_partial_waves)


                    * [`PawXmlSetup.root()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawXmlSetup.root)


                    * [`PawXmlSetup.summary`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawXmlSetup.summary)


                    * [`PawXmlSetup.supports_soc`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawXmlSetup.supports_soc)


                    * [`PawXmlSetup.yield_figs()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PawXmlSetup.yield_figs)


                * [`Pseudo`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Pseudo)


                    * [`Pseudo.Z`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Pseudo.Z)


                    * [`Pseudo.Z_val`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Pseudo.Z_val)


                    * [`Pseudo._abc_impl`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Pseudo._abc_impl)


                    * [`Pseudo.as_dict()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Pseudo.as_dict)


                    * [`Pseudo.as_pseudo()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Pseudo.as_pseudo)


                    * [`Pseudo.as_tmpfile()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Pseudo.as_tmpfile)


                    * [`Pseudo.basename`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Pseudo.basename)


                    * [`Pseudo.compute_md5()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Pseudo.compute_md5)


                    * [`Pseudo.djrepo_path`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Pseudo.djrepo_path)


                    * [`Pseudo.element`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Pseudo.element)


                    * [`Pseudo.filepath`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Pseudo.filepath)


                    * [`Pseudo.from_dict()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Pseudo.from_dict)


                    * [`Pseudo.from_file()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Pseudo.from_file)


                    * [`Pseudo.has_dojo_report`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Pseudo.has_dojo_report)


                    * [`Pseudo.has_hints`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Pseudo.has_hints)


                    * [`Pseudo.hint_for_accuracy()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Pseudo.hint_for_accuracy)


                    * [`Pseudo.isnc`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Pseudo.isnc)


                    * [`Pseudo.ispaw`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Pseudo.ispaw)


                    * [`Pseudo.l_local`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Pseudo.l_local)


                    * [`Pseudo.l_max`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Pseudo.l_max)


                    * [`Pseudo.md5()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Pseudo.md5)


                    * [`Pseudo.open_pspsfile()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Pseudo.open_pspsfile)


                    * [`Pseudo.summary`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Pseudo.summary)


                    * [`Pseudo.supports_soc`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Pseudo.supports_soc)


                    * [`Pseudo.symbol`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Pseudo.symbol)


                    * [`Pseudo.to_str()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Pseudo.to_str)


                    * [`Pseudo.to_string()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Pseudo.to_string)


                    * [`Pseudo.type`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.Pseudo.type)


                * [`PseudoParseError`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PseudoParseError)


                * [`PseudoParser`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PseudoParser)


                    * [`PseudoParser.Error`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PseudoParser.Error)


                    * [`PseudoParser._PSPCODES`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PseudoParser._PSPCODES)


                    * [`PseudoParser.parse()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PseudoParser.parse)


                    * [`PseudoParser.read_ppdesc()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PseudoParser.read_ppdesc)


                    * [`PseudoParser.scan_directory()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PseudoParser.scan_directory)


                * [`PseudoTable`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PseudoTable)


                    * [`PseudoTable._abc_impl`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PseudoTable._abc_impl)


                    * [`PseudoTable.all_combinations_for_elements()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PseudoTable.all_combinations_for_elements)


                    * [`PseudoTable.allnc`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PseudoTable.allnc)


                    * [`PseudoTable.allpaw`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PseudoTable.allpaw)


                    * [`PseudoTable.as_dict()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PseudoTable.as_dict)


                    * [`PseudoTable.as_table()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PseudoTable.as_table)


                    * [`PseudoTable.from_dict()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PseudoTable.from_dict)


                    * [`PseudoTable.from_dir()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PseudoTable.from_dir)


                    * [`PseudoTable.get_pseudos_for_structure()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PseudoTable.get_pseudos_for_structure)


                    * [`PseudoTable.is_complete()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PseudoTable.is_complete)


                    * [`PseudoTable.print_table()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PseudoTable.print_table)


                    * [`PseudoTable.pseudo_with_symbol()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PseudoTable.pseudo_with_symbol)


                    * [`PseudoTable.pseudos_with_symbols()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PseudoTable.pseudos_with_symbols)


                    * [`PseudoTable.select()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PseudoTable.select)


                    * [`PseudoTable.select_family()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PseudoTable.select_family)


                    * [`PseudoTable.select_rows()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PseudoTable.select_rows)


                    * [`PseudoTable.select_symbols()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PseudoTable.select_symbols)


                    * [`PseudoTable.sort_by_z()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PseudoTable.sort_by_z)


                    * [`PseudoTable.sorted()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PseudoTable.sorted)


                    * [`PseudoTable.to_table()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PseudoTable.to_table)


                    * [`PseudoTable.with_dojo_report()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PseudoTable.with_dojo_report)


                    * [`PseudoTable.zlist`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.PseudoTable.zlist)


                * [`RadialFunction`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.RadialFunction)


                * [`_dict_from_lines()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos._dict_from_lines)


                * [`_int_from_str()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos._int_from_str)


                * [`_read_nlines()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos._read_nlines)


                * [`l2str()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.l2str)


                * [`str2l()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.str2l)


                * [`straceback()`](pymatgen.io.abinit.md#pymatgen.io.abinit.pseudos.straceback)


            * [pymatgen.io.abinit.variable module](pymatgen.io.abinit.md#module-pymatgen.io.abinit.variable)


                * [`InputVariable`](pymatgen.io.abinit.md#pymatgen.io.abinit.variable.InputVariable)


                    * [`InputVariable.basename`](pymatgen.io.abinit.md#pymatgen.io.abinit.variable.InputVariable.basename)


                    * [`InputVariable.dataset`](pymatgen.io.abinit.md#pymatgen.io.abinit.variable.InputVariable.dataset)


                    * [`InputVariable.format_list()`](pymatgen.io.abinit.md#pymatgen.io.abinit.variable.InputVariable.format_list)


                    * [`InputVariable.format_list2d()`](pymatgen.io.abinit.md#pymatgen.io.abinit.variable.InputVariable.format_list2d)


                    * [`InputVariable.format_scalar()`](pymatgen.io.abinit.md#pymatgen.io.abinit.variable.InputVariable.format_scalar)


                    * [`InputVariable.get_value()`](pymatgen.io.abinit.md#pymatgen.io.abinit.variable.InputVariable.get_value)


                    * [`InputVariable.name`](pymatgen.io.abinit.md#pymatgen.io.abinit.variable.InputVariable.name)


                    * [`InputVariable.units`](pymatgen.io.abinit.md#pymatgen.io.abinit.variable.InputVariable.units)


                * [`flatten()`](pymatgen.io.abinit.md#pymatgen.io.abinit.variable.flatten)


        * [pymatgen.io.cp2k package](pymatgen.io.cp2k.md)




            * [pymatgen.io.cp2k.inputs module](pymatgen.io.cp2k.md#module-pymatgen.io.cp2k.inputs)


                * [`AtomicMetadata`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.AtomicMetadata)


                    * [`AtomicMetadata.info`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.AtomicMetadata.info)


                    * [`AtomicMetadata.element`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.AtomicMetadata.element)


                    * [`AtomicMetadata.potential`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.AtomicMetadata.potential)


                    * [`AtomicMetadata.name`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.AtomicMetadata.name)


                    * [`AtomicMetadata.alias_names`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.AtomicMetadata.alias_names)


                    * [`AtomicMetadata.filename`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.AtomicMetadata.filename)


                    * [`AtomicMetadata.version`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.AtomicMetadata.version)


                    * [`AtomicMetadata.alias_names`](pymatgen.io.cp2k.md#id0)


                    * [`AtomicMetadata.element`](pymatgen.io.cp2k.md#id1)


                    * [`AtomicMetadata.filename`](pymatgen.io.cp2k.md#id2)


                    * [`AtomicMetadata.get_hash()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.AtomicMetadata.get_hash)


                    * [`AtomicMetadata.get_str()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.AtomicMetadata.get_str)


                    * [`AtomicMetadata.get_string()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.AtomicMetadata.get_string)


                    * [`AtomicMetadata.info`](pymatgen.io.cp2k.md#id3)


                    * [`AtomicMetadata.name`](pymatgen.io.cp2k.md#id4)


                    * [`AtomicMetadata.potential`](pymatgen.io.cp2k.md#id5)


                    * [`AtomicMetadata.softmatch()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.AtomicMetadata.softmatch)


                    * [`AtomicMetadata.version`](pymatgen.io.cp2k.md#id6)


                * [`Band_Structure`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Band_Structure)


                    * [`Band_Structure.from_kpoints()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Band_Structure.from_kpoints)


                * [`BasisFile`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.BasisFile)


                    * [`BasisFile.from_str()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.BasisFile.from_str)


                * [`BasisInfo`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.BasisInfo)


                    * [`BasisInfo.electrons`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.BasisInfo.electrons)


                    * [`BasisInfo.core`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.BasisInfo.core)


                    * [`BasisInfo.valence`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.BasisInfo.valence)


                    * [`BasisInfo.polarization`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.BasisInfo.polarization)


                    * [`BasisInfo.diffuse`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.BasisInfo.diffuse)


                    * [`BasisInfo.cc`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.BasisInfo.cc)


                    * [`BasisInfo.pc`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.BasisInfo.pc)


                    * [`BasisInfo.sr`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.BasisInfo.sr)


                    * [`BasisInfo.molopt`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.BasisInfo.molopt)


                    * [`BasisInfo.admm`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.BasisInfo.admm)


                    * [`BasisInfo.lri`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.BasisInfo.lri)


                    * [`BasisInfo.contracted`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.BasisInfo.contracted)


                    * [`BasisInfo.xc`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.BasisInfo.xc)


                    * [`BasisInfo.admm`](pymatgen.io.cp2k.md#id7)


                    * [`BasisInfo.cc`](pymatgen.io.cp2k.md#id8)


                    * [`BasisInfo.contracted`](pymatgen.io.cp2k.md#id9)


                    * [`BasisInfo.core`](pymatgen.io.cp2k.md#id10)


                    * [`BasisInfo.diffuse`](pymatgen.io.cp2k.md#id11)


                    * [`BasisInfo.electrons`](pymatgen.io.cp2k.md#id12)


                    * [`BasisInfo.from_str()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.BasisInfo.from_str)


                    * [`BasisInfo.from_string()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.BasisInfo.from_string)


                    * [`BasisInfo.lri`](pymatgen.io.cp2k.md#id13)


                    * [`BasisInfo.molopt`](pymatgen.io.cp2k.md#id14)


                    * [`BasisInfo.pc`](pymatgen.io.cp2k.md#id15)


                    * [`BasisInfo.polarization`](pymatgen.io.cp2k.md#id16)


                    * [`BasisInfo.softmatch()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.BasisInfo.softmatch)


                    * [`BasisInfo.sr`](pymatgen.io.cp2k.md#id17)


                    * [`BasisInfo.valence`](pymatgen.io.cp2k.md#id18)


                    * [`BasisInfo.xc`](pymatgen.io.cp2k.md#id19)


                * [`BrokenSymmetry`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.BrokenSymmetry)


                    * [`BrokenSymmetry.from_el()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.BrokenSymmetry.from_el)


                * [`Cell`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Cell)


                * [`Coord`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Coord)


                * [`Cp2kInput`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Cp2kInput)


                    * [`Cp2kInput._from_dict()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Cp2kInput._from_dict)


                    * [`Cp2kInput._from_lines()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Cp2kInput._from_lines)


                    * [`Cp2kInput.from_file()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Cp2kInput.from_file)


                    * [`Cp2kInput.from_lines()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Cp2kInput.from_lines)


                    * [`Cp2kInput.from_str()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Cp2kInput.from_str)


                    * [`Cp2kInput.from_string()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Cp2kInput.from_string)


                    * [`Cp2kInput.get_str()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Cp2kInput.get_str)


                    * [`Cp2kInput.write_file()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Cp2kInput.write_file)


                * [`DOS`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.DOS)


                * [`DataFile`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.DataFile)


                    * [`DataFile.from_file()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.DataFile.from_file)


                    * [`DataFile.from_str()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.DataFile.from_str)


                    * [`DataFile.from_string()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.DataFile.from_string)


                    * [`DataFile.get_str()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.DataFile.get_str)


                    * [`DataFile.get_string()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.DataFile.get_string)


                    * [`DataFile.objects`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.DataFile.objects)


                    * [`DataFile.write_file()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.DataFile.write_file)


                * [`Davidson`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Davidson)


                * [`Dft`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Dft)


                * [`DftPlusU`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.DftPlusU)


                * [`Diagonalization`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Diagonalization)


                * [`E_Density_Cube`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.E_Density_Cube)


                * [`ForceEval`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.ForceEval)


                * [`GaussianTypeOrbitalBasisSet`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GaussianTypeOrbitalBasisSet)


                    * [`GaussianTypeOrbitalBasisSet.info`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GaussianTypeOrbitalBasisSet.info)


                    * [`GaussianTypeOrbitalBasisSet.nset`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GaussianTypeOrbitalBasisSet.nset)


                    * [`GaussianTypeOrbitalBasisSet.n`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GaussianTypeOrbitalBasisSet.n)


                    * [`GaussianTypeOrbitalBasisSet.lmax`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GaussianTypeOrbitalBasisSet.lmax)


                    * [`GaussianTypeOrbitalBasisSet.lmin`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GaussianTypeOrbitalBasisSet.lmin)


                    * [`GaussianTypeOrbitalBasisSet.nshell`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GaussianTypeOrbitalBasisSet.nshell)


                    * [`GaussianTypeOrbitalBasisSet.exponents`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GaussianTypeOrbitalBasisSet.exponents)


                    * [`GaussianTypeOrbitalBasisSet.coefficients`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GaussianTypeOrbitalBasisSet.coefficients)


                    * [`GaussianTypeOrbitalBasisSet.coefficients`](pymatgen.io.cp2k.md#id20)


                    * [`GaussianTypeOrbitalBasisSet.exponents`](pymatgen.io.cp2k.md#id21)


                    * [`GaussianTypeOrbitalBasisSet.from_str()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GaussianTypeOrbitalBasisSet.from_str)


                    * [`GaussianTypeOrbitalBasisSet.from_string()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GaussianTypeOrbitalBasisSet.from_string)


                    * [`GaussianTypeOrbitalBasisSet.get_keyword()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GaussianTypeOrbitalBasisSet.get_keyword)


                    * [`GaussianTypeOrbitalBasisSet.get_str()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GaussianTypeOrbitalBasisSet.get_str)


                    * [`GaussianTypeOrbitalBasisSet.get_string()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GaussianTypeOrbitalBasisSet.get_string)


                    * [`GaussianTypeOrbitalBasisSet.info`](pymatgen.io.cp2k.md#id22)


                    * [`GaussianTypeOrbitalBasisSet.lmax`](pymatgen.io.cp2k.md#id23)


                    * [`GaussianTypeOrbitalBasisSet.lmin`](pymatgen.io.cp2k.md#id24)


                    * [`GaussianTypeOrbitalBasisSet.n`](pymatgen.io.cp2k.md#id25)


                    * [`GaussianTypeOrbitalBasisSet.nexp`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GaussianTypeOrbitalBasisSet.nexp)


                    * [`GaussianTypeOrbitalBasisSet.nset`](pymatgen.io.cp2k.md#id26)


                    * [`GaussianTypeOrbitalBasisSet.nshell`](pymatgen.io.cp2k.md#id27)


                * [`Global`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Global)


                * [`GthPotential`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GthPotential)


                    * [`GthPotential.info`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GthPotential.info)


                    * [`GthPotential.n_elecs`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GthPotential.n_elecs)


                    * [`GthPotential.r_loc`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GthPotential.r_loc)


                    * [`GthPotential.nexp_ppl`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GthPotential.nexp_ppl)


                    * [`GthPotential.c_exp_ppl`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GthPotential.c_exp_ppl)


                    * [`GthPotential.radii`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GthPotential.radii)


                    * [`GthPotential.nprj`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GthPotential.nprj)


                    * [`GthPotential.nprj_ppnl`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GthPotential.nprj_ppnl)


                    * [`GthPotential.hprj_ppnl`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GthPotential.hprj_ppnl)


                    * [`GthPotential.c_exp_ppl`](pymatgen.io.cp2k.md#id28)


                    * [`GthPotential.from_section()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GthPotential.from_section)


                    * [`GthPotential.from_str()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GthPotential.from_str)


                    * [`GthPotential.from_string()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GthPotential.from_string)


                    * [`GthPotential.get_keyword()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GthPotential.get_keyword)


                    * [`GthPotential.get_section()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GthPotential.get_section)


                    * [`GthPotential.get_str()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GthPotential.get_str)


                    * [`GthPotential.get_string()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.GthPotential.get_string)


                    * [`GthPotential.hprj_ppnl`](pymatgen.io.cp2k.md#id29)


                    * [`GthPotential.n_elecs`](pymatgen.io.cp2k.md#id30)


                    * [`GthPotential.nexp_ppl`](pymatgen.io.cp2k.md#id31)


                    * [`GthPotential.nprj`](pymatgen.io.cp2k.md#id32)


                    * [`GthPotential.nprj_ppnl`](pymatgen.io.cp2k.md#id33)


                    * [`GthPotential.r_loc`](pymatgen.io.cp2k.md#id34)


                    * [`GthPotential.radii`](pymatgen.io.cp2k.md#id35)


                * [`Keyword`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Keyword)


                    * [`Keyword.as_dict()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Keyword.as_dict)


                    * [`Keyword.from_dict()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Keyword.from_dict)


                    * [`Keyword.from_str()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Keyword.from_str)


                    * [`Keyword.from_string()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Keyword.from_string)


                    * [`Keyword.get_str()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Keyword.get_str)


                    * [`Keyword.get_string()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Keyword.get_string)


                    * [`Keyword.verbosity()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Keyword.verbosity)


                * [`KeywordList`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.KeywordList)


                    * [`KeywordList.append()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.KeywordList.append)


                    * [`KeywordList.extend()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.KeywordList.extend)


                    * [`KeywordList.get_str()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.KeywordList.get_str)


                    * [`KeywordList.get_string()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.KeywordList.get_string)


                    * [`KeywordList.verbosity()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.KeywordList.verbosity)


                * [`Kind`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Kind)


                * [`Kpoint_Set`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Kpoint_Set)


                * [`Kpoints`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Kpoints)


                    * [`Kpoints.from_kpoints()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Kpoints.from_kpoints)


                * [`LDOS`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.LDOS)


                * [`MO_Cubes`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.MO_Cubes)


                * [`Mgrid`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Mgrid)


                * [`OrbitalTransformation`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.OrbitalTransformation)


                * [`PBE`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.PBE)


                * [`PDOS`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.PDOS)


                * [`PotentialFile`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.PotentialFile)


                    * [`PotentialFile.from_str()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.PotentialFile.from_str)


                * [`PotentialInfo`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.PotentialInfo)


                    * [`PotentialInfo.electrons`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.PotentialInfo.electrons)


                    * [`PotentialInfo.potential_type`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.PotentialInfo.potential_type)


                    * [`PotentialInfo.nlcc`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.PotentialInfo.nlcc)


                    * [`PotentialInfo.xc`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.PotentialInfo.xc)


                    * [`PotentialInfo.electrons`](pymatgen.io.cp2k.md#id36)


                    * [`PotentialInfo.from_str()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.PotentialInfo.from_str)


                    * [`PotentialInfo.from_string()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.PotentialInfo.from_string)


                    * [`PotentialInfo.nlcc`](pymatgen.io.cp2k.md#id37)


                    * [`PotentialInfo.potential_type`](pymatgen.io.cp2k.md#id38)


                    * [`PotentialInfo.softmatch()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.PotentialInfo.softmatch)


                    * [`PotentialInfo.xc`](pymatgen.io.cp2k.md#id39)


                * [`QS`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.QS)


                * [`Scf`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Scf)


                * [`Section`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Section)


                    * [`Section._get_str()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Section._get_str)


                    * [`Section._update()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Section._update)


                    * [`Section.add()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Section.add)


                    * [`Section.by_path()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Section.by_path)


                    * [`Section.check()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Section.check)


                    * [`Section.get()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Section.get)


                    * [`Section.get_keyword()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Section.get_keyword)


                    * [`Section.get_section()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Section.get_section)


                    * [`Section.get_str()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Section.get_str)


                    * [`Section.get_string()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Section.get_string)


                    * [`Section.inc()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Section.inc)


                    * [`Section.insert()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Section.insert)


                    * [`Section.safeset()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Section.safeset)


                    * [`Section.set()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Section.set)


                    * [`Section.setitem()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Section.setitem)


                    * [`Section.silence()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Section.silence)


                    * [`Section.unset()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Section.unset)


                    * [`Section.update()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Section.update)


                    * [`Section.verbosity()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Section.verbosity)


                * [`SectionList`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.SectionList)


                    * [`SectionList._get_str()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.SectionList._get_str)


                    * [`SectionList.append()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.SectionList.append)


                    * [`SectionList.extend()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.SectionList.extend)


                    * [`SectionList.get()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.SectionList.get)


                    * [`SectionList.get_str()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.SectionList.get_str)


                    * [`SectionList.get_string()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.SectionList.get_string)


                    * [`SectionList.verbosity()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.SectionList.verbosity)


                * [`Smear`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Smear)


                * [`Subsys`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Subsys)


                * [`V_Hartree_Cube`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.V_Hartree_Cube)


                * [`Xc_Functional`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.inputs.Xc_Functional)


            * [pymatgen.io.cp2k.outputs module](pymatgen.io.cp2k.md#module-pymatgen.io.cp2k.outputs)


                * [`Cp2kOutput`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput)


                    * [`Cp2kOutput._gauss_smear()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput._gauss_smear)


                    * [`Cp2kOutput.as_dict()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.as_dict)


                    * [`Cp2kOutput.band_structure`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.band_structure)


                    * [`Cp2kOutput.calculation_type`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.calculation_type)


                    * [`Cp2kOutput.charge`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.charge)


                    * [`Cp2kOutput.complete_dos`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.complete_dos)


                    * [`Cp2kOutput.completed`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.completed)


                    * [`Cp2kOutput.convergence()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.convergence)


                    * [`Cp2kOutput.cp2k_version`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.cp2k_version)


                    * [`Cp2kOutput.is_hubbard`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.is_hubbard)


                    * [`Cp2kOutput.is_metal`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.is_metal)


                    * [`Cp2kOutput.is_molecule`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.is_molecule)


                    * [`Cp2kOutput.multiplicity`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.multiplicity)


                    * [`Cp2kOutput.num_warnings`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.num_warnings)


                    * [`Cp2kOutput.parse_atomic_kind_info()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_atomic_kind_info)


                    * [`Cp2kOutput.parse_bandstructure()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_bandstructure)


                    * [`Cp2kOutput.parse_cell_params()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_cell_params)


                    * [`Cp2kOutput.parse_chi_tensor()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_chi_tensor)


                    * [`Cp2kOutput.parse_cp2k_params()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_cp2k_params)


                    * [`Cp2kOutput.parse_dft_params()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_dft_params)


                    * [`Cp2kOutput.parse_dos()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_dos)


                    * [`Cp2kOutput.parse_energies()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_energies)


                    * [`Cp2kOutput.parse_files()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_files)


                    * [`Cp2kOutput.parse_forces()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_forces)


                    * [`Cp2kOutput.parse_global_params()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_global_params)


                    * [`Cp2kOutput.parse_gtensor()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_gtensor)


                    * [`Cp2kOutput.parse_hirshfeld()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_hirshfeld)


                    * [`Cp2kOutput.parse_homo_lumo()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_homo_lumo)


                    * [`Cp2kOutput.parse_hyperfine()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_hyperfine)


                    * [`Cp2kOutput.parse_initial_structure()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_initial_structure)


                    * [`Cp2kOutput.parse_input()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_input)


                    * [`Cp2kOutput.parse_ionic_steps()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_ionic_steps)


                    * [`Cp2kOutput.parse_mo_eigenvalues()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_mo_eigenvalues)


                    * [`Cp2kOutput.parse_mulliken()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_mulliken)


                    * [`Cp2kOutput.parse_nmr_shift()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_nmr_shift)


                    * [`Cp2kOutput.parse_opt_steps()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_opt_steps)


                    * [`Cp2kOutput.parse_overlap_condition()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_overlap_condition)


                    * [`Cp2kOutput.parse_plus_u_params()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_plus_u_params)


                    * [`Cp2kOutput.parse_qs_params()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_qs_params)


                    * [`Cp2kOutput.parse_raman()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_raman)


                    * [`Cp2kOutput.parse_scf_opt()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_scf_opt)


                    * [`Cp2kOutput.parse_scf_params()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_scf_params)


                    * [`Cp2kOutput.parse_stresses()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_stresses)


                    * [`Cp2kOutput.parse_structures()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_structures)


                    * [`Cp2kOutput.parse_tddfpt()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_tddfpt)


                    * [`Cp2kOutput.parse_timing()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_timing)


                    * [`Cp2kOutput.parse_total_numbers()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.parse_total_numbers)


                    * [`Cp2kOutput.project_name`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.project_name)


                    * [`Cp2kOutput.ran_successfully()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.ran_successfully)


                    * [`Cp2kOutput.read_pattern()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.read_pattern)


                    * [`Cp2kOutput.read_table_pattern()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.read_table_pattern)


                    * [`Cp2kOutput.run_type`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.run_type)


                    * [`Cp2kOutput.spin_polarized`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.Cp2kOutput.spin_polarized)


                * [`parse_dos()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.parse_dos)


                * [`parse_energy_file()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.parse_energy_file)


                * [`parse_pdos()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.outputs.parse_pdos)


            * [pymatgen.io.cp2k.sets module](pymatgen.io.cp2k.md#module-pymatgen.io.cp2k.sets)


                * [`CellOptSet`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.CellOptSet)


                * [`Cp2kValidationError`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.Cp2kValidationError)


                    * [`Cp2kValidationError.CP2K_VERSION`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.Cp2kValidationError.CP2K_VERSION)


                * [`DftSet`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet)


                    * [`DftSet.activate_epr()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.activate_epr)


                    * [`DftSet.activate_fast_minimization()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.activate_fast_minimization)


                    * [`DftSet.activate_hybrid()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.activate_hybrid)


                    * [`DftSet.activate_hyperfine()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.activate_hyperfine)


                    * [`DftSet.activate_localize()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.activate_localize)


                    * [`DftSet.activate_motion()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.activate_motion)


                    * [`DftSet.activate_nmr()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.activate_nmr)


                    * [`DftSet.activate_nonperiodic()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.activate_nonperiodic)


                    * [`DftSet.activate_polar()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.activate_polar)


                    * [`DftSet.activate_robust_minimization()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.activate_robust_minimization)


                    * [`DftSet.activate_spinspin()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.activate_spinspin)


                    * [`DftSet.activate_tddfpt()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.activate_tddfpt)


                    * [`DftSet.activate_vdw_potential()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.activate_vdw_potential)


                    * [`DftSet.activate_very_strict_minimization()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.activate_very_strict_minimization)


                    * [`DftSet.create_subsys()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.create_subsys)


                    * [`DftSet.get_basis_and_potential()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.get_basis_and_potential)


                    * [`DftSet.get_cutoff_from_basis()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.get_cutoff_from_basis)


                    * [`DftSet.get_xc_functionals()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.get_xc_functionals)


                    * [`DftSet.modify_dft_print_iters()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.modify_dft_print_iters)


                    * [`DftSet.print_bandstructure()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.print_bandstructure)


                    * [`DftSet.print_dos()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.print_dos)


                    * [`DftSet.print_e_density()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.print_e_density)


                    * [`DftSet.print_forces()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.print_forces)


                    * [`DftSet.print_hirshfeld()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.print_hirshfeld)


                    * [`DftSet.print_ldos()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.print_ldos)


                    * [`DftSet.print_mo()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.print_mo)


                    * [`DftSet.print_mo_cubes()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.print_mo_cubes)


                    * [`DftSet.print_mulliken()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.print_mulliken)


                    * [`DftSet.print_pdos()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.print_pdos)


                    * [`DftSet.print_v_hartree()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.print_v_hartree)


                    * [`DftSet.set_charge()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.set_charge)


                    * [`DftSet.validate()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.validate)


                    * [`DftSet.write_basis_set_file()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.write_basis_set_file)


                    * [`DftSet.write_potential_file()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.DftSet.write_potential_file)


                * [`HybridCellOptSet`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.HybridCellOptSet)


                * [`HybridRelaxSet`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.HybridRelaxSet)


                * [`HybridStaticSet`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.HybridStaticSet)


                * [`RelaxSet`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.RelaxSet)


                * [`StaticSet`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.sets.StaticSet)


            * [pymatgen.io.cp2k.utils module](pymatgen.io.cp2k.md#module-pymatgen.io.cp2k.utils)


                * [`chunk()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.utils.chunk)


                * [`get_truncated_coulomb_cutoff()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.utils.get_truncated_coulomb_cutoff)


                * [`get_unique_site_indices()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.utils.get_unique_site_indices)


                * [`natural_keys()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.utils.natural_keys)


                * [`postprocessor()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.utils.postprocessor)


                * [`preprocessor()`](pymatgen.io.cp2k.md#pymatgen.io.cp2k.utils.preprocessor)


        * [pymatgen.io.exciting package](pymatgen.io.exciting.md)




            * [pymatgen.io.exciting.inputs module](pymatgen.io.exciting.md#module-pymatgen.io.exciting.inputs)


                * [`ExcitingInput`](pymatgen.io.exciting.md#pymatgen.io.exciting.inputs.ExcitingInput)


                    * [`ExcitingInput.structure`](pymatgen.io.exciting.md#pymatgen.io.exciting.inputs.ExcitingInput.structure)


                    * [`ExcitingInput.title`](pymatgen.io.exciting.md#pymatgen.io.exciting.inputs.ExcitingInput.title)


                    * [`ExcitingInput.lockxyz`](pymatgen.io.exciting.md#pymatgen.io.exciting.inputs.ExcitingInput.lockxyz)


                    * [`ExcitingInput._dicttoxml()`](pymatgen.io.exciting.md#pymatgen.io.exciting.inputs.ExcitingInput._dicttoxml)


                    * [`ExcitingInput._indent()`](pymatgen.io.exciting.md#pymatgen.io.exciting.inputs.ExcitingInput._indent)


                    * [`ExcitingInput.bohr2ang`](pymatgen.io.exciting.md#pymatgen.io.exciting.inputs.ExcitingInput.bohr2ang)


                    * [`ExcitingInput.from_file()`](pymatgen.io.exciting.md#pymatgen.io.exciting.inputs.ExcitingInput.from_file)


                    * [`ExcitingInput.from_str()`](pymatgen.io.exciting.md#pymatgen.io.exciting.inputs.ExcitingInput.from_str)


                    * [`ExcitingInput.from_string()`](pymatgen.io.exciting.md#pymatgen.io.exciting.inputs.ExcitingInput.from_string)


                    * [`ExcitingInput.lockxyz`](pymatgen.io.exciting.md#id0)


                    * [`ExcitingInput.write_etree()`](pymatgen.io.exciting.md#pymatgen.io.exciting.inputs.ExcitingInput.write_etree)


                    * [`ExcitingInput.write_file()`](pymatgen.io.exciting.md#pymatgen.io.exciting.inputs.ExcitingInput.write_file)


                    * [`ExcitingInput.write_string()`](pymatgen.io.exciting.md#pymatgen.io.exciting.inputs.ExcitingInput.write_string)


        * [pymatgen.io.feff package](pymatgen.io.feff.md)




            * [pymatgen.io.feff.inputs module](pymatgen.io.feff.md#module-pymatgen.io.feff.inputs)


                * [`Atoms`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Atoms)


                    * [`Atoms._set_cluster()`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Atoms._set_cluster)


                    * [`Atoms.atoms_string_from_file()`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Atoms.atoms_string_from_file)


                    * [`Atoms.cluster`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Atoms.cluster)


                    * [`Atoms.cluster_from_file()`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Atoms.cluster_from_file)


                    * [`Atoms.get_lines()`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Atoms.get_lines)


                    * [`Atoms.write_file()`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Atoms.write_file)


                * [`FeffParseError`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.FeffParseError)


                * [`Header`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Header)


                    * [`Header.formula`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Header.formula)


                    * [`Header.from_cif_file()`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Header.from_cif_file)


                    * [`Header.from_file()`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Header.from_file)


                    * [`Header.from_str()`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Header.from_str)


                    * [`Header.from_string()`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Header.from_string)


                    * [`Header.header_string_from_file()`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Header.header_string_from_file)


                    * [`Header.structure_symmetry`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Header.structure_symmetry)


                    * [`Header.write_file()`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Header.write_file)


                * [`Paths`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Paths)


                    * [`Paths.write_file()`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Paths.write_file)


                * [`Potential`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Potential)


                    * [`Potential.pot_dict_from_string()`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Potential.pot_dict_from_string)


                    * [`Potential.pot_string_from_file()`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Potential.pot_string_from_file)


                    * [`Potential.write_file()`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Potential.write_file)


                * [`Tags`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Tags)


                    * [`Tags._stringify_val()`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Tags._stringify_val)


                    * [`Tags.as_dict()`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Tags.as_dict)


                    * [`Tags.diff()`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Tags.diff)


                    * [`Tags.from_dict()`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Tags.from_dict)


                    * [`Tags.from_file()`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Tags.from_file)


                    * [`Tags.get_str()`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Tags.get_str)


                    * [`Tags.get_string()`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Tags.get_string)


                    * [`Tags.proc_val()`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Tags.proc_val)


                    * [`Tags.write_file()`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.Tags.write_file)


                * [`get_absorbing_atom_symbol_index()`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.get_absorbing_atom_symbol_index)


                * [`get_atom_map()`](pymatgen.io.feff.md#pymatgen.io.feff.inputs.get_atom_map)


            * [pymatgen.io.feff.outputs module](pymatgen.io.feff.md#module-pymatgen.io.feff.outputs)


                * [`Eels`](pymatgen.io.feff.md#pymatgen.io.feff.outputs.Eels)


                    * [`Eels.as_dict()`](pymatgen.io.feff.md#pymatgen.io.feff.outputs.Eels.as_dict)


                    * [`Eels.atomic_background`](pymatgen.io.feff.md#pymatgen.io.feff.outputs.Eels.atomic_background)


                    * [`Eels.energies`](pymatgen.io.feff.md#pymatgen.io.feff.outputs.Eels.energies)


                    * [`Eels.fine_structure`](pymatgen.io.feff.md#pymatgen.io.feff.outputs.Eels.fine_structure)


                    * [`Eels.from_file()`](pymatgen.io.feff.md#pymatgen.io.feff.outputs.Eels.from_file)


                    * [`Eels.total_spectrum`](pymatgen.io.feff.md#pymatgen.io.feff.outputs.Eels.total_spectrum)


                * [`LDos`](pymatgen.io.feff.md#pymatgen.io.feff.outputs.LDos)


                    * [`LDos.charge_transfer_from_file()`](pymatgen.io.feff.md#pymatgen.io.feff.outputs.LDos.charge_transfer_from_file)


                    * [`LDos.charge_transfer_to_string()`](pymatgen.io.feff.md#pymatgen.io.feff.outputs.LDos.charge_transfer_to_string)


                    * [`LDos.from_file()`](pymatgen.io.feff.md#pymatgen.io.feff.outputs.LDos.from_file)


                * [`Xmu`](pymatgen.io.feff.md#pymatgen.io.feff.outputs.Xmu)


                    * [`Xmu.as_dict()`](pymatgen.io.feff.md#pymatgen.io.feff.outputs.Xmu.as_dict)


                    * [`Xmu.calc`](pymatgen.io.feff.md#pymatgen.io.feff.outputs.Xmu.calc)


                    * [`Xmu.chi`](pymatgen.io.feff.md#pymatgen.io.feff.outputs.Xmu.chi)


                    * [`Xmu.e_fermi`](pymatgen.io.feff.md#pymatgen.io.feff.outputs.Xmu.e_fermi)


                    * [`Xmu.edge`](pymatgen.io.feff.md#pymatgen.io.feff.outputs.Xmu.edge)


                    * [`Xmu.energies`](pymatgen.io.feff.md#pymatgen.io.feff.outputs.Xmu.energies)


                    * [`Xmu.from_file()`](pymatgen.io.feff.md#pymatgen.io.feff.outputs.Xmu.from_file)


                    * [`Xmu.material_formula`](pymatgen.io.feff.md#pymatgen.io.feff.outputs.Xmu.material_formula)


                    * [`Xmu.mu`](pymatgen.io.feff.md#pymatgen.io.feff.outputs.Xmu.mu)


                    * [`Xmu.mu0`](pymatgen.io.feff.md#pymatgen.io.feff.outputs.Xmu.mu0)


                    * [`Xmu.relative_energies`](pymatgen.io.feff.md#pymatgen.io.feff.outputs.Xmu.relative_energies)


                    * [`Xmu.source`](pymatgen.io.feff.md#pymatgen.io.feff.outputs.Xmu.source)


                    * [`Xmu.wavenumber`](pymatgen.io.feff.md#pymatgen.io.feff.outputs.Xmu.wavenumber)


            * [pymatgen.io.feff.sets module](pymatgen.io.feff.md#module-pymatgen.io.feff.sets)


                * [`AbstractFeffInputSet`](pymatgen.io.feff.md#pymatgen.io.feff.sets.AbstractFeffInputSet)


                    * [`AbstractFeffInputSet._abc_impl`](pymatgen.io.feff.md#pymatgen.io.feff.sets.AbstractFeffInputSet._abc_impl)


                    * [`AbstractFeffInputSet.all_input()`](pymatgen.io.feff.md#pymatgen.io.feff.sets.AbstractFeffInputSet.all_input)


                    * [`AbstractFeffInputSet.atoms`](pymatgen.io.feff.md#pymatgen.io.feff.sets.AbstractFeffInputSet.atoms)


                    * [`AbstractFeffInputSet.header()`](pymatgen.io.feff.md#pymatgen.io.feff.sets.AbstractFeffInputSet.header)


                    * [`AbstractFeffInputSet.potential`](pymatgen.io.feff.md#pymatgen.io.feff.sets.AbstractFeffInputSet.potential)


                    * [`AbstractFeffInputSet.tags`](pymatgen.io.feff.md#pymatgen.io.feff.sets.AbstractFeffInputSet.tags)


                    * [`AbstractFeffInputSet.write_input()`](pymatgen.io.feff.md#pymatgen.io.feff.sets.AbstractFeffInputSet.write_input)


                * [`FEFFDictSet`](pymatgen.io.feff.md#pymatgen.io.feff.sets.FEFFDictSet)


                    * [`FEFFDictSet._abc_impl`](pymatgen.io.feff.md#pymatgen.io.feff.sets.FEFFDictSet._abc_impl)


                    * [`FEFFDictSet.atoms`](pymatgen.io.feff.md#pymatgen.io.feff.sets.FEFFDictSet.atoms)


                    * [`FEFFDictSet.from_directory()`](pymatgen.io.feff.md#pymatgen.io.feff.sets.FEFFDictSet.from_directory)


                    * [`FEFFDictSet.header()`](pymatgen.io.feff.md#pymatgen.io.feff.sets.FEFFDictSet.header)


                    * [`FEFFDictSet.potential`](pymatgen.io.feff.md#pymatgen.io.feff.sets.FEFFDictSet.potential)


                    * [`FEFFDictSet.tags`](pymatgen.io.feff.md#pymatgen.io.feff.sets.FEFFDictSet.tags)


                * [`MPEELSDictSet`](pymatgen.io.feff.md#pymatgen.io.feff.sets.MPEELSDictSet)


                    * [`MPEELSDictSet._abc_impl`](pymatgen.io.feff.md#pymatgen.io.feff.sets.MPEELSDictSet._abc_impl)


                * [`MPELNESSet`](pymatgen.io.feff.md#pymatgen.io.feff.sets.MPELNESSet)


                    * [`MPELNESSet.CONFIG`](pymatgen.io.feff.md#pymatgen.io.feff.sets.MPELNESSet.CONFIG)


                    * [`MPELNESSet._abc_impl`](pymatgen.io.feff.md#pymatgen.io.feff.sets.MPELNESSet._abc_impl)


                * [`MPEXAFSSet`](pymatgen.io.feff.md#pymatgen.io.feff.sets.MPEXAFSSet)


                    * [`MPEXAFSSet.CONFIG`](pymatgen.io.feff.md#pymatgen.io.feff.sets.MPEXAFSSet.CONFIG)


                    * [`MPEXAFSSet._abc_impl`](pymatgen.io.feff.md#pymatgen.io.feff.sets.MPEXAFSSet._abc_impl)


                * [`MPEXELFSSet`](pymatgen.io.feff.md#pymatgen.io.feff.sets.MPEXELFSSet)


                    * [`MPEXELFSSet.CONFIG`](pymatgen.io.feff.md#pymatgen.io.feff.sets.MPEXELFSSet.CONFIG)


                    * [`MPEXELFSSet._abc_impl`](pymatgen.io.feff.md#pymatgen.io.feff.sets.MPEXELFSSet._abc_impl)


                * [`MPXANESSet`](pymatgen.io.feff.md#pymatgen.io.feff.sets.MPXANESSet)


                    * [`MPXANESSet.CONFIG`](pymatgen.io.feff.md#pymatgen.io.feff.sets.MPXANESSet.CONFIG)


                    * [`MPXANESSet._abc_impl`](pymatgen.io.feff.md#pymatgen.io.feff.sets.MPXANESSet._abc_impl)


        * [pymatgen.io.lammps package](pymatgen.io.lammps.md)




            * [pymatgen.io.lammps.data module](pymatgen.io.lammps.md#module-pymatgen.io.lammps.data)


                * [`CombinedData`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.CombinedData)


                    * [`CombinedData.as_lammpsdata()`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.CombinedData.as_lammpsdata)


                    * [`CombinedData.disassemble()`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.CombinedData.disassemble)


                    * [`CombinedData.from_ff_and_topologies()`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.CombinedData.from_ff_and_topologies)


                    * [`CombinedData.from_files()`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.CombinedData.from_files)


                    * [`CombinedData.from_lammpsdata()`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.CombinedData.from_lammpsdata)


                    * [`CombinedData.from_structure()`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.CombinedData.from_structure)


                    * [`CombinedData.get_str()`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.CombinedData.get_str)


                    * [`CombinedData.get_string()`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.CombinedData.get_string)


                    * [`CombinedData.parse_xyz()`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.CombinedData.parse_xyz)


                    * [`CombinedData.structure`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.CombinedData.structure)


                * [`ForceField`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.ForceField)


                    * [`ForceField.masses`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.ForceField.masses)


                    * [`ForceField.force_field`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.ForceField.force_field)


                    * [`ForceField.maps`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.ForceField.maps)


                    * [`ForceField._is_valid()`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.ForceField._is_valid)


                    * [`ForceField._process_nonbond()`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.ForceField._process_nonbond)


                    * [`ForceField._process_topo()`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.ForceField._process_topo)


                    * [`ForceField.from_dict()`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.ForceField.from_dict)


                    * [`ForceField.from_file()`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.ForceField.from_file)


                    * [`ForceField.to_file()`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.ForceField.to_file)


                * [`LammpsBox`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.LammpsBox)


                    * [`LammpsBox.get_box_shift()`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.LammpsBox.get_box_shift)


                    * [`LammpsBox.get_str()`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.LammpsBox.get_str)


                    * [`LammpsBox.get_string()`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.LammpsBox.get_string)


                    * [`LammpsBox.to_lattice()`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.LammpsBox.to_lattice)


                    * [`LammpsBox.volume`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.LammpsBox.volume)


                * [`LammpsData`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.LammpsData)


                    * [`LammpsData.disassemble()`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.LammpsData.disassemble)


                    * [`LammpsData.from_ff_and_topologies()`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.LammpsData.from_ff_and_topologies)


                    * [`LammpsData.from_file()`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.LammpsData.from_file)


                    * [`LammpsData.from_structure()`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.LammpsData.from_structure)


                    * [`LammpsData.get_str()`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.LammpsData.get_str)


                    * [`LammpsData.get_string()`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.LammpsData.get_string)


                    * [`LammpsData.set_charge_atom()`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.LammpsData.set_charge_atom)


                    * [`LammpsData.set_charge_atom_type()`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.LammpsData.set_charge_atom_type)


                    * [`LammpsData.structure`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.LammpsData.structure)


                    * [`LammpsData.write_file()`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.LammpsData.write_file)


                * [`Topology`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.Topology)


                    * [`Topology.from_bonding()`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.Topology.from_bonding)


                * [`lattice_2_lmpbox()`](pymatgen.io.lammps.md#pymatgen.io.lammps.data.lattice_2_lmpbox)


            * [pymatgen.io.lammps.generators module](pymatgen.io.lammps.md#module-pymatgen.io.lammps.generators)


                * [`BaseLammpsGenerator`](pymatgen.io.lammps.md#pymatgen.io.lammps.generators.BaseLammpsGenerator)


                    * [`BaseLammpsGenerator.calc_type`](pymatgen.io.lammps.md#pymatgen.io.lammps.generators.BaseLammpsGenerator.calc_type)


                    * [`BaseLammpsGenerator.get_input_set()`](pymatgen.io.lammps.md#pymatgen.io.lammps.generators.BaseLammpsGenerator.get_input_set)


                    * [`BaseLammpsGenerator.keep_stages`](pymatgen.io.lammps.md#pymatgen.io.lammps.generators.BaseLammpsGenerator.keep_stages)


                    * [`BaseLammpsGenerator.settings`](pymatgen.io.lammps.md#pymatgen.io.lammps.generators.BaseLammpsGenerator.settings)


                    * [`BaseLammpsGenerator.template`](pymatgen.io.lammps.md#pymatgen.io.lammps.generators.BaseLammpsGenerator.template)


                * [`LammpsMinimization`](pymatgen.io.lammps.md#pymatgen.io.lammps.generators.LammpsMinimization)


                    * [`LammpsMinimization.atom_style`](pymatgen.io.lammps.md#pymatgen.io.lammps.generators.LammpsMinimization.atom_style)


                    * [`LammpsMinimization.boundary`](pymatgen.io.lammps.md#pymatgen.io.lammps.generators.LammpsMinimization.boundary)


                    * [`LammpsMinimization.dimension`](pymatgen.io.lammps.md#pymatgen.io.lammps.generators.LammpsMinimization.dimension)


                    * [`LammpsMinimization.force_field`](pymatgen.io.lammps.md#pymatgen.io.lammps.generators.LammpsMinimization.force_field)


                    * [`LammpsMinimization.read_data`](pymatgen.io.lammps.md#pymatgen.io.lammps.generators.LammpsMinimization.read_data)


                    * [`LammpsMinimization.settings`](pymatgen.io.lammps.md#pymatgen.io.lammps.generators.LammpsMinimization.settings)


                    * [`LammpsMinimization.template`](pymatgen.io.lammps.md#pymatgen.io.lammps.generators.LammpsMinimization.template)


                    * [`LammpsMinimization.units`](pymatgen.io.lammps.md#pymatgen.io.lammps.generators.LammpsMinimization.units)


            * [pymatgen.io.lammps.inputs module](pymatgen.io.lammps.md#module-pymatgen.io.lammps.inputs)


                * [`LammpsInputFile`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsInputFile)


                    * [`LammpsInputFile._add_command()`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsInputFile._add_command)


                    * [`LammpsInputFile._add_comment()`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsInputFile._add_comment)


                    * [`LammpsInputFile._check_stage_format()`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsInputFile._check_stage_format)


                    * [`LammpsInputFile._clean_lines()`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsInputFile._clean_lines)


                    * [`LammpsInputFile._get_blocks()`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsInputFile._get_blocks)


                    * [`LammpsInputFile._initialize_stage()`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsInputFile._initialize_stage)


                    * [`LammpsInputFile.add_commands()`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsInputFile.add_commands)


                    * [`LammpsInputFile.add_stage()`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsInputFile.add_stage)


                    * [`LammpsInputFile.append()`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsInputFile.append)


                    * [`LammpsInputFile.contains_command()`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsInputFile.contains_command)


                    * [`LammpsInputFile.from_file()`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsInputFile.from_file)


                    * [`LammpsInputFile.from_str()`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsInputFile.from_str)


                    * [`LammpsInputFile.from_string()`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsInputFile.from_string)


                    * [`LammpsInputFile.get_args()`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsInputFile.get_args)


                    * [`LammpsInputFile.get_str()`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsInputFile.get_str)


                    * [`LammpsInputFile.get_string()`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsInputFile.get_string)


                    * [`LammpsInputFile.merge_stages()`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsInputFile.merge_stages)


                    * [`LammpsInputFile.ncomments`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsInputFile.ncomments)


                    * [`LammpsInputFile.nstages`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsInputFile.nstages)


                    * [`LammpsInputFile.remove_command()`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsInputFile.remove_command)


                    * [`LammpsInputFile.remove_stage()`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsInputFile.remove_stage)


                    * [`LammpsInputFile.rename_stage()`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsInputFile.rename_stage)


                    * [`LammpsInputFile.set_args()`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsInputFile.set_args)


                    * [`LammpsInputFile.stages_names`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsInputFile.stages_names)


                    * [`LammpsInputFile.write_file()`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsInputFile.write_file)


                * [`LammpsRun`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsRun)


                    * [`LammpsRun.md()`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsRun.md)


                    * [`LammpsRun.template_dir`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsRun.template_dir)


                    * [`LammpsRun.write_inputs()`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsRun.write_inputs)


                * [`LammpsTemplateGen`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsTemplateGen)


                    * [`LammpsTemplateGen.get_input_set()`](pymatgen.io.lammps.md#pymatgen.io.lammps.inputs.LammpsTemplateGen.get_input_set)


            * [pymatgen.io.lammps.outputs module](pymatgen.io.lammps.md#module-pymatgen.io.lammps.outputs)


                * [`LammpsDump`](pymatgen.io.lammps.md#pymatgen.io.lammps.outputs.LammpsDump)


                    * [`LammpsDump.as_dict()`](pymatgen.io.lammps.md#pymatgen.io.lammps.outputs.LammpsDump.as_dict)


                    * [`LammpsDump.from_dict()`](pymatgen.io.lammps.md#pymatgen.io.lammps.outputs.LammpsDump.from_dict)


                    * [`LammpsDump.from_str()`](pymatgen.io.lammps.md#pymatgen.io.lammps.outputs.LammpsDump.from_str)


                    * [`LammpsDump.from_string()`](pymatgen.io.lammps.md#pymatgen.io.lammps.outputs.LammpsDump.from_string)


                * [`parse_lammps_dumps()`](pymatgen.io.lammps.md#pymatgen.io.lammps.outputs.parse_lammps_dumps)


                * [`parse_lammps_log()`](pymatgen.io.lammps.md#pymatgen.io.lammps.outputs.parse_lammps_log)


            * [pymatgen.io.lammps.sets module](pymatgen.io.lammps.md#module-pymatgen.io.lammps.sets)


                * [`LammpsInputSet`](pymatgen.io.lammps.md#pymatgen.io.lammps.sets.LammpsInputSet)


                    * [`LammpsInputSet._abc_impl`](pymatgen.io.lammps.md#pymatgen.io.lammps.sets.LammpsInputSet._abc_impl)


                    * [`LammpsInputSet.from_directory()`](pymatgen.io.lammps.md#pymatgen.io.lammps.sets.LammpsInputSet.from_directory)


                    * [`LammpsInputSet.validate()`](pymatgen.io.lammps.md#pymatgen.io.lammps.sets.LammpsInputSet.validate)


            * [pymatgen.io.lammps.utils module](pymatgen.io.lammps.md#module-pymatgen.io.lammps.utils)


                * [`LammpsRunner`](pymatgen.io.lammps.md#pymatgen.io.lammps.utils.LammpsRunner)


                    * [`LammpsRunner.run()`](pymatgen.io.lammps.md#pymatgen.io.lammps.utils.LammpsRunner.run)


                * [`Polymer`](pymatgen.io.lammps.md#pymatgen.io.lammps.utils.Polymer)


                    * [`Polymer._add_monomer()`](pymatgen.io.lammps.md#pymatgen.io.lammps.utils.Polymer._add_monomer)


                    * [`Polymer._align_monomer()`](pymatgen.io.lammps.md#pymatgen.io.lammps.utils.Polymer._align_monomer)


                    * [`Polymer._create()`](pymatgen.io.lammps.md#pymatgen.io.lammps.utils.Polymer._create)


                    * [`Polymer._next_move_direction()`](pymatgen.io.lammps.md#pymatgen.io.lammps.utils.Polymer._next_move_direction)


        * [pymatgen.io.lobster package](pymatgen.io.lobster.md)




            * [pymatgen.io.lobster.inputs module](pymatgen.io.lobster.md#module-pymatgen.io.lobster.inputs)


                * [`Lobsterin`](pymatgen.io.lobster.md#pymatgen.io.lobster.inputs.Lobsterin)


                    * [`Lobsterin.AVAILABLE_KEYWORDS`](pymatgen.io.lobster.md#pymatgen.io.lobster.inputs.Lobsterin.AVAILABLE_KEYWORDS)


                    * [`Lobsterin.BOOLEAN_KEYWORDS`](pymatgen.io.lobster.md#pymatgen.io.lobster.inputs.Lobsterin.BOOLEAN_KEYWORDS)


                    * [`Lobsterin.FLOAT_KEYWORDS`](pymatgen.io.lobster.md#pymatgen.io.lobster.inputs.Lobsterin.FLOAT_KEYWORDS)


                    * [`Lobsterin.LISTKEYWORDS`](pymatgen.io.lobster.md#pymatgen.io.lobster.inputs.Lobsterin.LISTKEYWORDS)


                    * [`Lobsterin.STRING_KEYWORDS`](pymatgen.io.lobster.md#pymatgen.io.lobster.inputs.Lobsterin.STRING_KEYWORDS)


                    * [`Lobsterin._get_nbands()`](pymatgen.io.lobster.md#pymatgen.io.lobster.inputs.Lobsterin._get_nbands)


                    * [`Lobsterin._get_potcar_symbols()`](pymatgen.io.lobster.md#pymatgen.io.lobster.inputs.Lobsterin._get_potcar_symbols)


                    * [`Lobsterin.as_dict()`](pymatgen.io.lobster.md#pymatgen.io.lobster.inputs.Lobsterin.as_dict)


                    * [`Lobsterin.diff()`](pymatgen.io.lobster.md#pymatgen.io.lobster.inputs.Lobsterin.diff)


                    * [`Lobsterin.from_dict()`](pymatgen.io.lobster.md#pymatgen.io.lobster.inputs.Lobsterin.from_dict)


                    * [`Lobsterin.from_file()`](pymatgen.io.lobster.md#pymatgen.io.lobster.inputs.Lobsterin.from_file)


                    * [`Lobsterin.get_all_possible_basis_functions()`](pymatgen.io.lobster.md#pymatgen.io.lobster.inputs.Lobsterin.get_all_possible_basis_functions)


                    * [`Lobsterin.get_basis()`](pymatgen.io.lobster.md#pymatgen.io.lobster.inputs.Lobsterin.get_basis)


                    * [`Lobsterin.standard_calculations_from_vasp_files()`](pymatgen.io.lobster.md#pymatgen.io.lobster.inputs.Lobsterin.standard_calculations_from_vasp_files)


                    * [`Lobsterin.write_INCAR()`](pymatgen.io.lobster.md#pymatgen.io.lobster.inputs.Lobsterin.write_INCAR)


                    * [`Lobsterin.write_KPOINTS()`](pymatgen.io.lobster.md#pymatgen.io.lobster.inputs.Lobsterin.write_KPOINTS)


                    * [`Lobsterin.write_POSCAR_with_standard_primitive()`](pymatgen.io.lobster.md#pymatgen.io.lobster.inputs.Lobsterin.write_POSCAR_with_standard_primitive)


                    * [`Lobsterin.write_lobsterin()`](pymatgen.io.lobster.md#pymatgen.io.lobster.inputs.Lobsterin.write_lobsterin)


                * [`get_all_possible_basis_combinations()`](pymatgen.io.lobster.md#pymatgen.io.lobster.inputs.get_all_possible_basis_combinations)


            * [pymatgen.io.lobster.lobsterenv module](pymatgen.io.lobster.md#module-pymatgen.io.lobster.lobsterenv)


                * [`ICOHPNeighborsInfo`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.ICOHPNeighborsInfo)


                    * [`ICOHPNeighborsInfo._asdict()`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.ICOHPNeighborsInfo._asdict)


                    * [`ICOHPNeighborsInfo._field_defaults`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.ICOHPNeighborsInfo._field_defaults)


                    * [`ICOHPNeighborsInfo._fields`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.ICOHPNeighborsInfo._fields)


                    * [`ICOHPNeighborsInfo._make()`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.ICOHPNeighborsInfo._make)


                    * [`ICOHPNeighborsInfo._replace()`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.ICOHPNeighborsInfo._replace)


                    * [`ICOHPNeighborsInfo.atoms`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.ICOHPNeighborsInfo.atoms)


                    * [`ICOHPNeighborsInfo.central_isites`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.ICOHPNeighborsInfo.central_isites)


                    * [`ICOHPNeighborsInfo.labels`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.ICOHPNeighborsInfo.labels)


                    * [`ICOHPNeighborsInfo.list_icohps`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.ICOHPNeighborsInfo.list_icohps)


                    * [`ICOHPNeighborsInfo.n_bonds`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.ICOHPNeighborsInfo.n_bonds)


                    * [`ICOHPNeighborsInfo.total_icohp`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.ICOHPNeighborsInfo.total_icohp)


                * [`LobsterLightStructureEnvironments`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.LobsterLightStructureEnvironments)


                    * [`LobsterLightStructureEnvironments.as_dict()`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.LobsterLightStructureEnvironments.as_dict)


                    * [`LobsterLightStructureEnvironments.from_Lobster()`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.LobsterLightStructureEnvironments.from_Lobster)


                    * [`LobsterLightStructureEnvironments.uniquely_determines_coordination_environments`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.LobsterLightStructureEnvironments.uniquely_determines_coordination_environments)


                * [`LobsterNeighbors`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.LobsterNeighbors)


                    * [`LobsterNeighbors._adapt_extremum_to_add_cond()`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.LobsterNeighbors._adapt_extremum_to_add_cond)


                    * [`LobsterNeighbors._determine_unit_cell()`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.LobsterNeighbors._determine_unit_cell)


                    * [`LobsterNeighbors._evaluate_ce()`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.LobsterNeighbors._evaluate_ce)


                    * [`LobsterNeighbors._find_environments()`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.LobsterNeighbors._find_environments)


                    * [`LobsterNeighbors._find_relevant_atoms_additional_condition()`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.LobsterNeighbors._find_relevant_atoms_additional_condition)


                    * [`LobsterNeighbors._get_atomnumber()`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.LobsterNeighbors._get_atomnumber)


                    * [`LobsterNeighbors._get_icohps()`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.LobsterNeighbors._get_icohps)


                    * [`LobsterNeighbors._get_limit_from_extremum()`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.LobsterNeighbors._get_limit_from_extremum)


                    * [`LobsterNeighbors._get_plot_label()`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.LobsterNeighbors._get_plot_label)


                    * [`LobsterNeighbors._split_string()`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.LobsterNeighbors._split_string)


                    * [`LobsterNeighbors.anion_types`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.LobsterNeighbors.anion_types)


                    * [`LobsterNeighbors.get_anion_types()`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.LobsterNeighbors.get_anion_types)


                    * [`LobsterNeighbors.get_info_cohps_to_neighbors()`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.LobsterNeighbors.get_info_cohps_to_neighbors)


                    * [`LobsterNeighbors.get_info_icohps_between_neighbors()`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.LobsterNeighbors.get_info_icohps_between_neighbors)


                    * [`LobsterNeighbors.get_info_icohps_to_neighbors()`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.LobsterNeighbors.get_info_icohps_to_neighbors)


                    * [`LobsterNeighbors.get_light_structure_environment()`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.LobsterNeighbors.get_light_structure_environment)


                    * [`LobsterNeighbors.get_nn_info()`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.LobsterNeighbors.get_nn_info)


                    * [`LobsterNeighbors.molecules_allowed`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.LobsterNeighbors.molecules_allowed)


                    * [`LobsterNeighbors.plot_cohps_of_neighbors()`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.LobsterNeighbors.plot_cohps_of_neighbors)


                    * [`LobsterNeighbors.structures_allowed`](pymatgen.io.lobster.md#pymatgen.io.lobster.lobsterenv.LobsterNeighbors.structures_allowed)


            * [pymatgen.io.lobster.outputs module](pymatgen.io.lobster.md#module-pymatgen.io.lobster.outputs)


                * [`Bandoverlaps`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Bandoverlaps)


                    * [`Bandoverlaps.maxDeviation`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Bandoverlaps.maxDeviation)


                    * [`Bandoverlaps._read()`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Bandoverlaps._read)


                    * [`Bandoverlaps.has_good_quality_check_occupied_bands()`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Bandoverlaps.has_good_quality_check_occupied_bands)


                    * [`Bandoverlaps.has_good_quality_maxDeviation()`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Bandoverlaps.has_good_quality_maxDeviation)


                * [`Charge`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Charge)


                    * [`Charge.atomlist`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Charge.atomlist)


                    * [`Charge.types`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Charge.types)


                    * [`Charge.Mulliken`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Charge.Mulliken)


                    * [`Charge.Loewdin`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Charge.Loewdin)


                    * [`Charge.num_atoms`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Charge.num_atoms)


                    * [`Charge.get_structure_with_charges()`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Charge.get_structure_with_charges)


                * [`Cohpcar`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Cohpcar)


                    * [`Cohpcar.cohp_data`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Cohpcar.cohp_data)


                    * [`Cohpcar.efermi`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Cohpcar.efermi)


                    * [`Cohpcar.energies`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Cohpcar.energies)


                    * [`Cohpcar.is_spin_polarized`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Cohpcar.is_spin_polarized)


                    * [`Cohpcar.orb_cohp`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Cohpcar.orb_cohp)


                    * [`Cohpcar._get_bond_data()`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Cohpcar._get_bond_data)


                * [`Doscar`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Doscar)


                    * [`Doscar.completedos`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Doscar.completedos)


                    * [`Doscar.pdos`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Doscar.pdos)


                    * [`Doscar.tdos`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Doscar.tdos)


                    * [`Doscar.energies`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Doscar.energies)


                    * [`Doscar.tdensities`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Doscar.tdensities)


                    * [`Doscar.itdensities`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Doscar.itdensities)


                    * [`Doscar.is_spin_polarized`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Doscar.is_spin_polarized)


                    * [`Doscar._parse_doscar()`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Doscar._parse_doscar)


                    * [`Doscar.completedos`](pymatgen.io.lobster.md#id0)


                    * [`Doscar.energies`](pymatgen.io.lobster.md#id1)


                    * [`Doscar.is_spin_polarized`](pymatgen.io.lobster.md#id2)


                    * [`Doscar.itdensities`](pymatgen.io.lobster.md#id3)


                    * [`Doscar.pdos`](pymatgen.io.lobster.md#id4)


                    * [`Doscar.tdensities`](pymatgen.io.lobster.md#id5)


                    * [`Doscar.tdos`](pymatgen.io.lobster.md#id6)


                * [`Fatband`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Fatband)


                    * [`Fatband.efermi`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Fatband.efermi)


                    * [`Fatband.eigenvals`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Fatband.eigenvals)


                    * [`Fatband.is_spin_polarized`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Fatband.is_spin_polarized)


                    * [`Fatband.kpoints_array`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Fatband.kpoints_array)


                    * [`Fatband.label_dict`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Fatband.label_dict)


                    * [`Fatband.lattice`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Fatband.lattice)


                    * [`Fatband.nbands`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Fatband.nbands)


                    * [`Fatband.p_eigenvals`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Fatband.p_eigenvals)


                    * [`Fatband.structure`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Fatband.structure)


                    * [`Fatband.get_bandstructure()`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Fatband.get_bandstructure)


                * [`Grosspop`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Grosspop)


                    * [`Grosspop.list_dict_grosspop`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Grosspop.list_dict_grosspop)


                    * [`Grosspop.get_structure_with_total_grosspop()`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Grosspop.get_structure_with_total_grosspop)


                * [`Icohplist`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Icohplist)


                    * [`Icohplist.are_coops`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Icohplist.are_coops)


                    * [`Icohplist.is_spin_polarized`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Icohplist.is_spin_polarized)


                    * [`Icohplist.Icohplist`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Icohplist.Icohplist)


                    * [`Icohplist.IcohpCollection`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Icohplist.IcohpCollection)


                    * [`Icohplist.icohpcollection`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Icohplist.icohpcollection)


                    * [`Icohplist.icohplist`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Icohplist.icohplist)


                * [`Lobsterout`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout)


                    * [`Lobsterout.basis_functions`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout.basis_functions)


                    * [`Lobsterout.basis_type`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout.basis_type)


                    * [`Lobsterout.charge_spilling`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout.charge_spilling)


                    * [`Lobsterout.dft_program`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout.dft_program)


                    * [`Lobsterout.elements`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout.elements)


                    * [`Lobsterout.has_charge`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout.has_charge)


                    * [`Lobsterout.has_cohpcar`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout.has_cohpcar)


                    * [`Lobsterout.has_madelung`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout.has_madelung)


                    * [`Lobsterout.has_coopcar`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout.has_coopcar)


                    * [`Lobsterout.has_cobicar`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout.has_cobicar)


                    * [`Lobsterout.has_doscar`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout.has_doscar)


                    * [`Lobsterout.has_doscar_lso`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout.has_doscar_lso)


                    * [`Lobsterout.has_projection`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout.has_projection)


                    * [`Lobsterout.has_bandoverlaps`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout.has_bandoverlaps)


                    * [`Lobsterout.has_density_of_energies`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout.has_density_of_energies)


                    * [`Lobsterout.has_fatbands`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout.has_fatbands)


                    * [`Lobsterout.has_grosspopulation`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout.has_grosspopulation)


                    * [`Lobsterout.info_lines`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout.info_lines)


                    * [`Lobsterout.info_orthonormalization`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout.info_orthonormalization)


                    * [`Lobsterout.is_restart_from_projection`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout.is_restart_from_projection)


                    * [`Lobsterout.lobster_version`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout.lobster_version)


                    * [`Lobsterout.number_of_spins`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout.number_of_spins)


                    * [`Lobsterout.number_of_threads`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout.number_of_threads)


                    * [`Lobsterout.timing`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout.timing)


                    * [`Lobsterout.total_spilling`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout.total_spilling)


                    * [`Lobsterout.warning_lines`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout.warning_lines)


                    * [`Lobsterout._get_all_info_lines()`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout._get_all_info_lines)


                    * [`Lobsterout._get_all_warning_lines()`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout._get_all_warning_lines)


                    * [`Lobsterout._get_dft_program()`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout._get_dft_program)


                    * [`Lobsterout._get_elements_basistype_basisfunctions()`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout._get_elements_basistype_basisfunctions)


                    * [`Lobsterout._get_lobster_version()`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout._get_lobster_version)


                    * [`Lobsterout._get_number_of_spins()`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout._get_number_of_spins)


                    * [`Lobsterout._get_spillings()`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout._get_spillings)


                    * [`Lobsterout._get_threads()`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout._get_threads)


                    * [`Lobsterout._get_timing()`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout._get_timing)


                    * [`Lobsterout._get_warning_orthonormalization()`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout._get_warning_orthonormalization)


                    * [`Lobsterout._has_fatband()`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout._has_fatband)


                    * [`Lobsterout.get_doc()`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Lobsterout.get_doc)


                * [`MadelungEnergies`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.MadelungEnergies)


                    * [`MadelungEnergies.madelungenergies_Mulliken`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.MadelungEnergies.madelungenergies_Mulliken)


                    * [`MadelungEnergies.madelungenergies_Loewdin`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.MadelungEnergies.madelungenergies_Loewdin)


                    * [`MadelungEnergies.ewald_splitting`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.MadelungEnergies.ewald_splitting)


                * [`SitePotential`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.SitePotential)


                    * [`SitePotential.atomlist`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.SitePotential.atomlist)


                    * [`SitePotential.types`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.SitePotential.types)


                    * [`SitePotential.num_atoms`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.SitePotential.num_atoms)


                    * [`SitePotential.sitepotentials_Mulliken`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.SitePotential.sitepotentials_Mulliken)


                    * [`SitePotential.sitepotentials_Loewdin`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.SitePotential.sitepotentials_Loewdin)


                    * [`SitePotential.madelung_Mulliken`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.SitePotential.madelung_Mulliken)


                    * [`SitePotential.madelung_Loewdin`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.SitePotential.madelung_Loewdin)


                    * [`SitePotential.ewald_splitting`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.SitePotential.ewald_splitting)


                    * [`SitePotential.get_structure_with_site_potentials()`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.SitePotential.get_structure_with_site_potentials)


                * [`Wavefunction`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Wavefunction)


                    * [`Wavefunction.grid`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Wavefunction.grid)


                    * [`Wavefunction.points`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Wavefunction.points)


                    * [`Wavefunction.real`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Wavefunction.real)


                    * [`Wavefunction.imaginary`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Wavefunction.imaginary)


                    * [`Wavefunction.distance`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Wavefunction.distance)


                    * [`Wavefunction._parse_file()`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Wavefunction._parse_file)


                    * [`Wavefunction.get_volumetricdata_density()`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Wavefunction.get_volumetricdata_density)


                    * [`Wavefunction.get_volumetricdata_imaginary()`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Wavefunction.get_volumetricdata_imaginary)


                    * [`Wavefunction.get_volumetricdata_real()`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Wavefunction.get_volumetricdata_real)


                    * [`Wavefunction.set_volumetric_data()`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Wavefunction.set_volumetric_data)


                    * [`Wavefunction.write_file()`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.Wavefunction.write_file)


                * [`get_orb_from_str()`](pymatgen.io.lobster.md#pymatgen.io.lobster.outputs.get_orb_from_str)


        * [pymatgen.io.qchem package](pymatgen.io.qchem.md)




            * [pymatgen.io.qchem.inputs module](pymatgen.io.qchem.md#module-pymatgen.io.qchem.inputs)


                * [`QCInput`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput)


                    * [`QCInput.almo_template()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.almo_template)


                    * [`QCInput.cdft_template()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.cdft_template)


                    * [`QCInput.find_sections()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.find_sections)


                    * [`QCInput.from_file()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.from_file)


                    * [`QCInput.from_multi_jobs_file()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.from_multi_jobs_file)


                    * [`QCInput.from_str()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.from_str)


                    * [`QCInput.geom_opt_template()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.geom_opt_template)


                    * [`QCInput.get_str()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.get_str)


                    * [`QCInput.get_string()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.get_string)


                    * [`QCInput.molecule_template()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.molecule_template)


                    * [`QCInput.multi_job_string()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.multi_job_string)


                    * [`QCInput.nbo_template()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.nbo_template)


                    * [`QCInput.opt_template()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.opt_template)


                    * [`QCInput.pcm_nonels_template()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.pcm_nonels_template)


                    * [`QCInput.pcm_template()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.pcm_template)


                    * [`QCInput.plots_template()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.plots_template)


                    * [`QCInput.read_almo()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.read_almo)


                    * [`QCInput.read_cdft()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.read_cdft)


                    * [`QCInput.read_geom_opt()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.read_geom_opt)


                    * [`QCInput.read_molecule()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.read_molecule)


                    * [`QCInput.read_nbo()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.read_nbo)


                    * [`QCInput.read_opt()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.read_opt)


                    * [`QCInput.read_pcm()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.read_pcm)


                    * [`QCInput.read_pcm_nonels()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.read_pcm_nonels)


                    * [`QCInput.read_plots()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.read_plots)


                    * [`QCInput.read_rem()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.read_rem)


                    * [`QCInput.read_scan()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.read_scan)


                    * [`QCInput.read_smx()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.read_smx)


                    * [`QCInput.read_solvent()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.read_solvent)


                    * [`QCInput.read_svp()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.read_svp)


                    * [`QCInput.read_vdw()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.read_vdw)


                    * [`QCInput.rem_template()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.rem_template)


                    * [`QCInput.scan_template()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.scan_template)


                    * [`QCInput.smx_template()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.smx_template)


                    * [`QCInput.solvent_template()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.solvent_template)


                    * [`QCInput.svp_template()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.svp_template)


                    * [`QCInput.van_der_waals_template()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.van_der_waals_template)


                    * [`QCInput.write_multi_job_file()`](pymatgen.io.qchem.md#pymatgen.io.qchem.inputs.QCInput.write_multi_job_file)


            * [pymatgen.io.qchem.outputs module](pymatgen.io.qchem.md#module-pymatgen.io.qchem.outputs)


                * [`QCOutput`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.QCOutput)


                    * [`QCOutput._check_completion_errors()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.QCOutput._check_completion_errors)


                    * [`QCOutput._detect_general_warnings()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.QCOutput._detect_general_warnings)


                    * [`QCOutput._get_grad_format_length()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.QCOutput._get_grad_format_length)


                    * [`QCOutput._read_SCF()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.QCOutput._read_SCF)


                    * [`QCOutput._read_almo_msdft()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.QCOutput._read_almo_msdft)


                    * [`QCOutput._read_cdft()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.QCOutput._read_cdft)


                    * [`QCOutput._read_charge_and_multiplicity()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.QCOutput._read_charge_and_multiplicity)


                    * [`QCOutput._read_charges_and_dipoles()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.QCOutput._read_charges_and_dipoles)


                    * [`QCOutput._read_cmirs_information()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.QCOutput._read_cmirs_information)


                    * [`QCOutput._read_coefficient_matrix()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.QCOutput._read_coefficient_matrix)


                    * [`QCOutput._read_eigenvalues()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.QCOutput._read_eigenvalues)


                    * [`QCOutput._read_fock_matrix()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.QCOutput._read_fock_matrix)


                    * [`QCOutput._read_force_data()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.QCOutput._read_force_data)


                    * [`QCOutput._read_frequency_data()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.QCOutput._read_frequency_data)


                    * [`QCOutput._read_geometries()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.QCOutput._read_geometries)


                    * [`QCOutput._read_gradients()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.QCOutput._read_gradients)


                    * [`QCOutput._read_isosvp_information()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.QCOutput._read_isosvp_information)


                    * [`QCOutput._read_nbo_data()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.QCOutput._read_nbo_data)


                    * [`QCOutput._read_optimization_data()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.QCOutput._read_optimization_data)


                    * [`QCOutput._read_pcm_information()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.QCOutput._read_pcm_information)


                    * [`QCOutput._read_scan_data()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.QCOutput._read_scan_data)


                    * [`QCOutput._read_smd_information()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.QCOutput._read_smd_information)


                    * [`QCOutput._read_species_and_inital_geometry()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.QCOutput._read_species_and_inital_geometry)


                    * [`QCOutput.as_dict()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.QCOutput.as_dict)


                    * [`QCOutput.multiple_outputs_from_file()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.QCOutput.multiple_outputs_from_file)


                * [`check_for_structure_changes()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.check_for_structure_changes)


                * [`get_percentage()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.get_percentage)


                * [`jump_to_header()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.jump_to_header)


                * [`nbo_parser()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.nbo_parser)


                * [`parse_hybridization_character()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.parse_hybridization_character)


                * [`parse_hyperbonds()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.parse_hyperbonds)


                * [`parse_natural_populations()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.parse_natural_populations)


                * [`parse_perturbation_energy()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.parse_perturbation_energy)


                * [`z_int()`](pymatgen.io.qchem.md#pymatgen.io.qchem.outputs.z_int)


            * [pymatgen.io.qchem.sets module](pymatgen.io.qchem.md#module-pymatgen.io.qchem.sets)


                * [`ForceSet`](pymatgen.io.qchem.md#pymatgen.io.qchem.sets.ForceSet)


                * [`FreqSet`](pymatgen.io.qchem.md#pymatgen.io.qchem.sets.FreqSet)


                * [`OptSet`](pymatgen.io.qchem.md#pymatgen.io.qchem.sets.OptSet)


                * [`PESScanSet`](pymatgen.io.qchem.md#pymatgen.io.qchem.sets.PESScanSet)


                * [`QChemDictSet`](pymatgen.io.qchem.md#pymatgen.io.qchem.sets.QChemDictSet)


                    * [`QChemDictSet.write()`](pymatgen.io.qchem.md#pymatgen.io.qchem.sets.QChemDictSet.write)


                * [`SinglePointSet`](pymatgen.io.qchem.md#pymatgen.io.qchem.sets.SinglePointSet)


                * [`TransitionStateSet`](pymatgen.io.qchem.md#pymatgen.io.qchem.sets.TransitionStateSet)


            * [pymatgen.io.qchem.utils module](pymatgen.io.qchem.md#module-pymatgen.io.qchem.utils)


                * [`lower_and_check_unique()`](pymatgen.io.qchem.md#pymatgen.io.qchem.utils.lower_and_check_unique)


                * [`process_parsed_HESS()`](pymatgen.io.qchem.md#pymatgen.io.qchem.utils.process_parsed_HESS)


                * [`process_parsed_coords()`](pymatgen.io.qchem.md#pymatgen.io.qchem.utils.process_parsed_coords)


                * [`process_parsed_fock_matrix()`](pymatgen.io.qchem.md#pymatgen.io.qchem.utils.process_parsed_fock_matrix)


                * [`read_matrix_pattern()`](pymatgen.io.qchem.md#pymatgen.io.qchem.utils.read_matrix_pattern)


                * [`read_pattern()`](pymatgen.io.qchem.md#pymatgen.io.qchem.utils.read_pattern)


                * [`read_table_pattern()`](pymatgen.io.qchem.md#pymatgen.io.qchem.utils.read_table_pattern)


        * [pymatgen.io.vasp package](pymatgen.io.vasp.md)




            * [pymatgen.io.vasp.help module](pymatgen.io.vasp.md#module-pymatgen.io.vasp.help)


                * [`VaspDoc`](pymatgen.io.vasp.md#pymatgen.io.vasp.help.VaspDoc)


                    * [`VaspDoc.get_help()`](pymatgen.io.vasp.md#pymatgen.io.vasp.help.VaspDoc.get_help)


                    * [`VaspDoc.get_incar_tags()`](pymatgen.io.vasp.md#pymatgen.io.vasp.help.VaspDoc.get_incar_tags)


                    * [`VaspDoc.print_help()`](pymatgen.io.vasp.md#pymatgen.io.vasp.help.VaspDoc.print_help)


                    * [`VaspDoc.print_jupyter_help()`](pymatgen.io.vasp.md#pymatgen.io.vasp.help.VaspDoc.print_jupyter_help)


            * [pymatgen.io.vasp.inputs module](pymatgen.io.vasp.md#module-pymatgen.io.vasp.inputs)


                * [`BadIncarWarning`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.BadIncarWarning)


                * [`Incar`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Incar)


                    * [`Incar.as_dict()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Incar.as_dict)


                    * [`Incar.check_params()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Incar.check_params)


                    * [`Incar.diff()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Incar.diff)


                    * [`Incar.from_dict()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Incar.from_dict)


                    * [`Incar.from_file()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Incar.from_file)


                    * [`Incar.from_str()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Incar.from_str)


                    * [`Incar.from_string()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Incar.from_string)


                    * [`Incar.get_str()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Incar.get_str)


                    * [`Incar.get_string()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Incar.get_string)


                    * [`Incar.proc_val()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Incar.proc_val)


                    * [`Incar.write_file()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Incar.write_file)


                * [`Kpoints`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Kpoints)


                    * [`Kpoints.as_dict()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Kpoints.as_dict)


                    * [`Kpoints.automatic()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Kpoints.automatic)


                    * [`Kpoints.automatic_density()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Kpoints.automatic_density)


                    * [`Kpoints.automatic_density_by_lengths()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Kpoints.automatic_density_by_lengths)


                    * [`Kpoints.automatic_density_by_vol()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Kpoints.automatic_density_by_vol)


                    * [`Kpoints.automatic_gamma_density()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Kpoints.automatic_gamma_density)


                    * [`Kpoints.automatic_linemode()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Kpoints.automatic_linemode)


                    * [`Kpoints.from_dict()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Kpoints.from_dict)


                    * [`Kpoints.from_file()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Kpoints.from_file)


                    * [`Kpoints.from_str()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Kpoints.from_str)


                    * [`Kpoints.from_string()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Kpoints.from_string)


                    * [`Kpoints.gamma_automatic()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Kpoints.gamma_automatic)


                    * [`Kpoints.monkhorst_automatic()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Kpoints.monkhorst_automatic)


                    * [`Kpoints.style`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Kpoints.style)


                    * [`Kpoints.supported_modes`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Kpoints.supported_modes)


                    * [`Kpoints.write_file()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Kpoints.write_file)


                * [`KpointsSupportedModes`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.KpointsSupportedModes)


                    * [`KpointsSupportedModes.Automatic`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.KpointsSupportedModes.Automatic)


                    * [`KpointsSupportedModes.Cartesian`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.KpointsSupportedModes.Cartesian)


                    * [`KpointsSupportedModes.Gamma`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.KpointsSupportedModes.Gamma)


                    * [`KpointsSupportedModes.Line_mode`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.KpointsSupportedModes.Line_mode)


                    * [`KpointsSupportedModes.Monkhorst`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.KpointsSupportedModes.Monkhorst)


                    * [`KpointsSupportedModes.Reciprocal`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.KpointsSupportedModes.Reciprocal)


                    * [`KpointsSupportedModes.from_str()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.KpointsSupportedModes.from_str)


                    * [`KpointsSupportedModes.from_string()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.KpointsSupportedModes.from_string)


                * [`Orbital`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Orbital)


                    * [`Orbital.E`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Orbital.E)


                    * [`Orbital._asdict()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Orbital._asdict)


                    * [`Orbital._field_defaults`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Orbital._field_defaults)


                    * [`Orbital._fields`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Orbital._fields)


                    * [`Orbital._make()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Orbital._make)


                    * [`Orbital._replace()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Orbital._replace)


                    * [`Orbital.j`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Orbital.j)


                    * [`Orbital.l`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Orbital.l)


                    * [`Orbital.n`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Orbital.n)


                    * [`Orbital.occ`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Orbital.occ)


                * [`OrbitalDescription`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.OrbitalDescription)


                    * [`OrbitalDescription.E`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.OrbitalDescription.E)


                    * [`OrbitalDescription.Rcut`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.OrbitalDescription.Rcut)


                    * [`OrbitalDescription.Rcut2`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.OrbitalDescription.Rcut2)


                    * [`OrbitalDescription.Type`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.OrbitalDescription.Type)


                    * [`OrbitalDescription.Type2`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.OrbitalDescription.Type2)


                    * [`OrbitalDescription._asdict()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.OrbitalDescription._asdict)


                    * [`OrbitalDescription._field_defaults`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.OrbitalDescription._field_defaults)


                    * [`OrbitalDescription._fields`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.OrbitalDescription._fields)


                    * [`OrbitalDescription._make()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.OrbitalDescription._make)


                    * [`OrbitalDescription._replace()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.OrbitalDescription._replace)


                    * [`OrbitalDescription.l`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.OrbitalDescription.l)


                * [`Poscar`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Poscar)


                    * [`Poscar.structure`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Poscar.structure)


                    * [`Poscar.comment`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Poscar.comment)


                    * [`Poscar.true_names`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Poscar.true_names)


                    * [`Poscar.selective_dynamics`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Poscar.selective_dynamics)


                    * [`Poscar.velocities`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Poscar.velocities)


                    * [`Poscar.predictor_corrector`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Poscar.predictor_corrector)


                    * [`Poscar.predictor_corrector_preamble`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Poscar.predictor_corrector_preamble)


                    * [`Poscar.temperature`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Poscar.temperature)


                    * [`Poscar.as_dict()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Poscar.as_dict)


                    * [`Poscar.from_dict()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Poscar.from_dict)


                    * [`Poscar.from_file()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Poscar.from_file)


                    * [`Poscar.from_str()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Poscar.from_str)


                    * [`Poscar.from_string()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Poscar.from_string)


                    * [`Poscar.get_str()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Poscar.get_str)


                    * [`Poscar.get_string()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Poscar.get_string)


                    * [`Poscar.natoms`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Poscar.natoms)


                    * [`Poscar.predictor_corrector`](pymatgen.io.vasp.md#id0)


                    * [`Poscar.predictor_corrector_preamble`](pymatgen.io.vasp.md#id1)


                    * [`Poscar.selective_dynamics`](pymatgen.io.vasp.md#id2)


                    * [`Poscar.set_temperature()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Poscar.set_temperature)


                    * [`Poscar.site_symbols`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Poscar.site_symbols)


                    * [`Poscar.velocities`](pymatgen.io.vasp.md#id3)


                    * [`Poscar.write_file()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Poscar.write_file)


                * [`Potcar`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Potcar)


                    * [`Potcar.FUNCTIONAL_CHOICES`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Potcar.FUNCTIONAL_CHOICES)


                    * [`Potcar.as_dict()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Potcar.as_dict)


                    * [`Potcar.from_dict()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Potcar.from_dict)


                    * [`Potcar.from_file()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Potcar.from_file)


                    * [`Potcar.set_symbols()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Potcar.set_symbols)


                    * [`Potcar.spec`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Potcar.spec)


                    * [`Potcar.symbols`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Potcar.symbols)


                    * [`Potcar.write_file()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.Potcar.write_file)


                * [`PotcarSingle`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.PotcarSingle)


                    * [`PotcarSingle.data`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.PotcarSingle.data)


                    * [`PotcarSingle.keywords`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.PotcarSingle.keywords)


                    * [`PotcarSingle.atomic_no`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.PotcarSingle.atomic_no)


                    * [`PotcarSingle.electron_configuration`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.PotcarSingle.electron_configuration)


                    * [`PotcarSingle.element`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.PotcarSingle.element)


                    * [`PotcarSingle.from_file()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.PotcarSingle.from_file)


                    * [`PotcarSingle.from_symbol_and_functional()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.PotcarSingle.from_symbol_and_functional)


                    * [`PotcarSingle.functional`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.PotcarSingle.functional)


                    * [`PotcarSingle.functional_class`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.PotcarSingle.functional_class)


                    * [`PotcarSingle.functional_dir`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.PotcarSingle.functional_dir)


                    * [`PotcarSingle.functional_tags`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.PotcarSingle.functional_tags)


                    * [`PotcarSingle.get_potcar_file_hash()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.PotcarSingle.get_potcar_file_hash)


                    * [`PotcarSingle.get_potcar_hash()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.PotcarSingle.get_potcar_hash)


                    * [`PotcarSingle.get_sha256_file_hash()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.PotcarSingle.get_sha256_file_hash)


                    * [`PotcarSingle.identify_potcar()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.PotcarSingle.identify_potcar)


                    * [`PotcarSingle.nelectrons`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.PotcarSingle.nelectrons)


                    * [`PotcarSingle.parse_functions`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.PotcarSingle.parse_functions)


                    * [`PotcarSingle.potential_type`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.PotcarSingle.potential_type)


                    * [`PotcarSingle.symbol`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.PotcarSingle.symbol)


                    * [`PotcarSingle.verify_potcar()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.PotcarSingle.verify_potcar)


                    * [`PotcarSingle.write_file()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.PotcarSingle.write_file)


                * [`UnknownPotcarWarning`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.UnknownPotcarWarning)


                * [`VaspInput`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.VaspInput)


                    * [`VaspInput.as_dict()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.VaspInput.as_dict)


                    * [`VaspInput.from_dict()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.VaspInput.from_dict)


                    * [`VaspInput.from_directory()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.VaspInput.from_directory)


                    * [`VaspInput.run_vasp()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.VaspInput.run_vasp)


                    * [`VaspInput.write_input()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs.VaspInput.write_input)


                * [`_parse_bool()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs._parse_bool)


                * [`_parse_float()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs._parse_float)


                * [`_parse_int()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs._parse_int)


                * [`_parse_list()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs._parse_list)


                * [`_parse_string()`](pymatgen.io.vasp.md#pymatgen.io.vasp.inputs._parse_string)


            * [pymatgen.io.vasp.optics module](pymatgen.io.vasp.md#module-pymatgen.io.vasp.optics)


                * [`DielectricFunctionCalculator`](pymatgen.io.vasp.md#pymatgen.io.vasp.optics.DielectricFunctionCalculator)


                    * [`DielectricFunctionCalculator.cder`](pymatgen.io.vasp.md#pymatgen.io.vasp.optics.DielectricFunctionCalculator.cder)


                    * [`DielectricFunctionCalculator.cder_imag`](pymatgen.io.vasp.md#pymatgen.io.vasp.optics.DielectricFunctionCalculator.cder_imag)


                    * [`DielectricFunctionCalculator.cder_real`](pymatgen.io.vasp.md#pymatgen.io.vasp.optics.DielectricFunctionCalculator.cder_real)


                    * [`DielectricFunctionCalculator.cshift`](pymatgen.io.vasp.md#pymatgen.io.vasp.optics.DielectricFunctionCalculator.cshift)


                    * [`DielectricFunctionCalculator.deltae`](pymatgen.io.vasp.md#pymatgen.io.vasp.optics.DielectricFunctionCalculator.deltae)


                    * [`DielectricFunctionCalculator.efermi`](pymatgen.io.vasp.md#pymatgen.io.vasp.optics.DielectricFunctionCalculator.efermi)


                    * [`DielectricFunctionCalculator.eigs`](pymatgen.io.vasp.md#pymatgen.io.vasp.optics.DielectricFunctionCalculator.eigs)


                    * [`DielectricFunctionCalculator.from_directory()`](pymatgen.io.vasp.md#pymatgen.io.vasp.optics.DielectricFunctionCalculator.from_directory)


                    * [`DielectricFunctionCalculator.from_vasp_objects()`](pymatgen.io.vasp.md#pymatgen.io.vasp.optics.DielectricFunctionCalculator.from_vasp_objects)


                    * [`DielectricFunctionCalculator.get_epsilon()`](pymatgen.io.vasp.md#pymatgen.io.vasp.optics.DielectricFunctionCalculator.get_epsilon)


                    * [`DielectricFunctionCalculator.ismear`](pymatgen.io.vasp.md#pymatgen.io.vasp.optics.DielectricFunctionCalculator.ismear)


                    * [`DielectricFunctionCalculator.ispin`](pymatgen.io.vasp.md#pymatgen.io.vasp.optics.DielectricFunctionCalculator.ispin)


                    * [`DielectricFunctionCalculator.kweights`](pymatgen.io.vasp.md#pymatgen.io.vasp.optics.DielectricFunctionCalculator.kweights)


                    * [`DielectricFunctionCalculator.nedos`](pymatgen.io.vasp.md#pymatgen.io.vasp.optics.DielectricFunctionCalculator.nedos)


                    * [`DielectricFunctionCalculator.plot_weighted_transition_data()`](pymatgen.io.vasp.md#pymatgen.io.vasp.optics.DielectricFunctionCalculator.plot_weighted_transition_data)


                    * [`DielectricFunctionCalculator.sigma`](pymatgen.io.vasp.md#pymatgen.io.vasp.optics.DielectricFunctionCalculator.sigma)


                    * [`DielectricFunctionCalculator.volume`](pymatgen.io.vasp.md#pymatgen.io.vasp.optics.DielectricFunctionCalculator.volume)


                * [`delta_func()`](pymatgen.io.vasp.md#pymatgen.io.vasp.optics.delta_func)


                * [`delta_methfessel_paxton()`](pymatgen.io.vasp.md#pymatgen.io.vasp.optics.delta_methfessel_paxton)


                * [`epsilon_imag()`](pymatgen.io.vasp.md#pymatgen.io.vasp.optics.epsilon_imag)


                * [`get_delta()`](pymatgen.io.vasp.md#pymatgen.io.vasp.optics.get_delta)


                * [`get_step()`](pymatgen.io.vasp.md#pymatgen.io.vasp.optics.get_step)


                * [`kramers_kronig()`](pymatgen.io.vasp.md#pymatgen.io.vasp.optics.kramers_kronig)


                * [`step_func()`](pymatgen.io.vasp.md#pymatgen.io.vasp.optics.step_func)


                * [`step_methfessel_paxton()`](pymatgen.io.vasp.md#pymatgen.io.vasp.optics.step_methfessel_paxton)


            * [pymatgen.io.vasp.outputs module](pymatgen.io.vasp.md#module-pymatgen.io.vasp.outputs)


                * [`BSVasprun`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.BSVasprun)


                    * [`BSVasprun.as_dict()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.BSVasprun.as_dict)


                * [`Chgcar`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Chgcar)


                    * [`Chgcar.from_file()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Chgcar.from_file)


                    * [`Chgcar.net_magnetization`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Chgcar.net_magnetization)


                * [`Dynmat`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Dynmat)


                    * [`Dynmat.data`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Dynmat.data)


                    * [`Dynmat.get_phonon_frequencies()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Dynmat.get_phonon_frequencies)


                    * [`Dynmat.masses`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Dynmat.masses)


                    * [`Dynmat.natoms`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Dynmat.natoms)


                    * [`Dynmat.ndisps`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Dynmat.ndisps)


                    * [`Dynmat.nspecs`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Dynmat.nspecs)


                * [`Eigenval`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Eigenval)


                    * [`Eigenval.filename`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Eigenval.filename)


                    * [`Eigenval.occu_tol`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Eigenval.occu_tol)


                    * [`Eigenval.ispin`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Eigenval.ispin)


                    * [`Eigenval.nelect`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Eigenval.nelect)


                    * [`Eigenval.nkpt`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Eigenval.nkpt)


                    * [`Eigenval.nbands`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Eigenval.nbands)


                    * [`Eigenval.kpoints`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Eigenval.kpoints)


                    * [`Eigenval.kpoints_weights`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Eigenval.kpoints_weights)


                    * [`Eigenval.eigenvalues`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Eigenval.eigenvalues)


                    * [`Eigenval.eigenvalue_band_properties`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Eigenval.eigenvalue_band_properties)


                * [`Elfcar`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Elfcar)


                    * [`Elfcar.from_file()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Elfcar.from_file)


                    * [`Elfcar.get_alpha()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Elfcar.get_alpha)


                * [`Locpot`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Locpot)


                    * [`Locpot.from_file()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Locpot.from_file)


                * [`Oszicar`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Oszicar)


                    * [`Oszicar.electronic_steps`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Oszicar.electronic_steps)


                    * [`Oszicar.ionic_steps`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Oszicar.ionic_steps)


                    * [`Oszicar.all_energies`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Oszicar.all_energies)


                    * [`Oszicar.as_dict()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Oszicar.as_dict)


                    * [`Oszicar.final_energy`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Oszicar.final_energy)


                * [`Outcar`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar)


                    * [`Outcar.magnetization`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.magnetization)


                    * [`Outcar.chemical_shielding`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.chemical_shielding)


                    * [`Outcar.unsym_cs_tensor`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.unsym_cs_tensor)


                    * [`Outcar.cs_g0_contribution`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.cs_g0_contribution)


                    * [`Outcar.cs_core_contribution`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.cs_core_contribution)


                    * [`Outcar.efg`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.efg)


                    * [`Outcar.charge`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.charge)


                    * [`Outcar.is_stopped`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.is_stopped)


                    * [`Outcar.run_stats`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.run_stats)


                    * [`Outcar.elastic_tensor`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.elastic_tensor)


                    * [`Outcar.drift`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.drift)


                    * [`Outcar.ngf`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.ngf)


                    * [`Outcar.sampling_radii`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.sampling_radii)


                    * [`Outcar.electrostatic_potential`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.electrostatic_potential)


                    * [`Outcar.final_energy_contribs`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.final_energy_contribs)


                    * [`Outcar.efermi`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.efermi)


                    * [`Outcar.filename`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.filename)


                    * [`Outcar.final_energy`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.final_energy)


                    * [`Outcar.final_energy_wo_entrp`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.final_energy_wo_entrp)


                    * [`Outcar.final_fr_energy`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.final_fr_energy)


                    * [`Outcar.has_onsite_density_matrices`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.has_onsite_density_matrices)


                    * [`Outcar.lcalcpol`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.lcalcpol)


                    * [`Outcar.lepsilon`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.lepsilon)


                    * [`Outcar.nelect`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.nelect)


                    * [`Outcar.spin`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.spin)


                    * [`Outcar.total_mag`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.total_mag)


                    * [`Outcar._parse_sci_notation()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar._parse_sci_notation)


                    * [`Outcar.as_dict()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.as_dict)


                    * [`Outcar.read_avg_core_poten()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.read_avg_core_poten)


                    * [`Outcar.read_chemical_shielding()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.read_chemical_shielding)


                    * [`Outcar.read_core_state_eigen()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.read_core_state_eigen)


                    * [`Outcar.read_corrections()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.read_corrections)


                    * [`Outcar.read_cs_core_contribution()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.read_cs_core_contribution)


                    * [`Outcar.read_cs_g0_contribution()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.read_cs_g0_contribution)


                    * [`Outcar.read_cs_raw_symmetrized_tensors()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.read_cs_raw_symmetrized_tensors)


                    * [`Outcar.read_elastic_tensor()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.read_elastic_tensor)


                    * [`Outcar.read_electrostatic_potential()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.read_electrostatic_potential)


                    * [`Outcar.read_fermi_contact_shift()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.read_fermi_contact_shift)


                    * [`Outcar.read_freq_dielectric()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.read_freq_dielectric)


                    * [`Outcar.read_igpar()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.read_igpar)


                    * [`Outcar.read_internal_strain_tensor()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.read_internal_strain_tensor)


                    * [`Outcar.read_lcalcpol()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.read_lcalcpol)


                    * [`Outcar.read_lepsilon()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.read_lepsilon)


                    * [`Outcar.read_lepsilon_ionic()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.read_lepsilon_ionic)


                    * [`Outcar.read_neb()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.read_neb)


                    * [`Outcar.read_nmr_efg()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.read_nmr_efg)


                    * [`Outcar.read_nmr_efg_tensor()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.read_nmr_efg_tensor)


                    * [`Outcar.read_onsite_density_matrices()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.read_onsite_density_matrices)


                    * [`Outcar.read_pattern()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.read_pattern)


                    * [`Outcar.read_piezo_tensor()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.read_piezo_tensor)


                    * [`Outcar.read_pseudo_zval()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.read_pseudo_zval)


                    * [`Outcar.read_table_pattern()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Outcar.read_table_pattern)


                * [`Procar`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Procar)


                    * [`Procar.data`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Procar.data)


                    * [`Procar.weights`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Procar.weights)


                    * [`Procar.phase_factors`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Procar.phase_factors)


                    * [`Procar.nbands`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Procar.nbands)


                    * [`Procar.nkpoints`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Procar.nkpoints)


                    * [`Procar.nions`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Procar.nions)


                    * [`Procar.get_occupation()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Procar.get_occupation)


                    * [`Procar.get_projection_on_elements()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Procar.get_projection_on_elements)


                * [`UnconvergedVASPWarning`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.UnconvergedVASPWarning)


                * [`VaspParseError`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.VaspParseError)


                * [`Vasprun`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun)


                    * [`Vasprun.ionic_steps`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.ionic_steps)


                    * [`Vasprun.tdos`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.tdos)


                    * [`Vasprun.idos`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.idos)


                    * [`Vasprun.pdos`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.pdos)


                    * [`Vasprun.efermi`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.efermi)


                    * [`Vasprun.eigenvalues`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.eigenvalues)


                    * [`Vasprun.projected_eigenvalues`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.projected_eigenvalues)


                    * [`Vasprun.projected_magnetisation`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.projected_magnetisation)


                    * [`Vasprun.other_dielectric`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.other_dielectric)


                    * [`Vasprun.nionic_steps`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.nionic_steps)


                    * [`Vasprun.force_constants`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.force_constants)


                    * [`Vasprun.normalmode_eigenvals`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.normalmode_eigenvals)


                    * [`Vasprun.normalmode_eigenvecs`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.normalmode_eigenvecs)


                    * [`Vasprun.md_data`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.md_data)


                    * [`Vasprun.incar`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.incar)


                    * [`Vasprun.parameters`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.parameters)


                    * [`Vasprun.kpoints`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.kpoints)


                    * [`Vasprun.actual_kpoints`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.actual_kpoints)


                    * [`Vasprun.actual_kpoints_weights`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.actual_kpoints_weights)


                    * [`Vasprun.atomic_symbols`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.atomic_symbols)


                    * [`Vasprun.potcar_symbols`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.potcar_symbols)


                    * [`Vasprun._parse()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun._parse)


                    * [`Vasprun._parse_atominfo()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun._parse_atominfo)


                    * [`Vasprun._parse_calculation()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun._parse_calculation)


                    * [`Vasprun._parse_chemical_shielding_calculation()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun._parse_chemical_shielding_calculation)


                    * [`Vasprun._parse_diel()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun._parse_diel)


                    * [`Vasprun._parse_dos()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun._parse_dos)


                    * [`Vasprun._parse_dynmat()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun._parse_dynmat)


                    * [`Vasprun._parse_eigen()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun._parse_eigen)


                    * [`Vasprun._parse_kpoints()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun._parse_kpoints)


                    * [`Vasprun._parse_optical_transition()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun._parse_optical_transition)


                    * [`Vasprun._parse_params()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun._parse_params)


                    * [`Vasprun._parse_projected_eigen()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun._parse_projected_eigen)


                    * [`Vasprun._parse_structure()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun._parse_structure)


                    * [`Vasprun.as_dict()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.as_dict)


                    * [`Vasprun.calculate_efermi()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.calculate_efermi)


                    * [`Vasprun.complete_dos`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.complete_dos)


                    * [`Vasprun.complete_dos_normalized`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.complete_dos_normalized)


                    * [`Vasprun.converged`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.converged)


                    * [`Vasprun.converged_electronic`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.converged_electronic)


                    * [`Vasprun.converged_ionic`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.converged_ionic)


                    * [`Vasprun.dielectric`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.dielectric)


                    * [`Vasprun.eigenvalue_band_properties`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.eigenvalue_band_properties)


                    * [`Vasprun.epsilon_ionic`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.epsilon_ionic)


                    * [`Vasprun.epsilon_static`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.epsilon_static)


                    * [`Vasprun.epsilon_static_wolfe`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.epsilon_static_wolfe)


                    * [`Vasprun.final_energy`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.final_energy)


                    * [`Vasprun.get_band_structure()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.get_band_structure)


                    * [`Vasprun.get_computed_entry()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.get_computed_entry)


                    * [`Vasprun.get_potcars()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.get_potcars)


                    * [`Vasprun.get_trajectory()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.get_trajectory)


                    * [`Vasprun.hubbards`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.hubbards)


                    * [`Vasprun.is_hubbard`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.is_hubbard)


                    * [`Vasprun.is_spin`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.is_spin)


                    * [`Vasprun.optical_absorption_coeff`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.optical_absorption_coeff)


                    * [`Vasprun.run_type`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.run_type)


                    * [`Vasprun.structures`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.structures)


                    * [`Vasprun.update_charge_from_potcar()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.update_charge_from_potcar)


                    * [`Vasprun.update_potcar_spec()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Vasprun.update_potcar_spec)


                * [`VolumetricData`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.VolumetricData)


                    * [`VolumetricData.parse_file()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.VolumetricData.parse_file)


                    * [`VolumetricData.write_file()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.VolumetricData.write_file)


                * [`WSWQ`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.WSWQ)


                    * [`WSWQ.nspin`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.WSWQ.nspin)


                    * [`WSWQ.nkpoints`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.WSWQ.nkpoints)


                    * [`WSWQ.nbands`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.WSWQ.nbands)


                    * [`WSWQ.me_real`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.WSWQ.me_real)


                    * [`WSWQ.me_imag`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.WSWQ.me_imag)


                    * [`WSWQ.data`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.WSWQ.data)


                    * [`WSWQ.from_file()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.WSWQ.from_file)


                    * [`WSWQ.me_imag`](pymatgen.io.vasp.md#id4)


                    * [`WSWQ.me_real`](pymatgen.io.vasp.md#id5)


                    * [`WSWQ.nbands`](pymatgen.io.vasp.md#id6)


                    * [`WSWQ.nkpoints`](pymatgen.io.vasp.md#id7)


                    * [`WSWQ.nspin`](pymatgen.io.vasp.md#id8)


                * [`Wavecar`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Wavecar)


                    * [`Wavecar.filename`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Wavecar.filename)


                    * [`Wavecar.vasp_type`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Wavecar.vasp_type)


                    * [`Wavecar.nk`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Wavecar.nk)


                    * [`Wavecar.nb`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Wavecar.nb)


                    * [`Wavecar.encut`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Wavecar.encut)


                    * [`Wavecar.efermi`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Wavecar.efermi)


                    * [`Wavecar.a`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Wavecar.a)


                    * [`Wavecar.b`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Wavecar.b)


                    * [`Wavecar.vol`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Wavecar.vol)


                    * [`Wavecar.kpoints`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Wavecar.kpoints)


                    * [`Wavecar.band_energy`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Wavecar.band_energy)


                    * [`Wavecar.Gpoints`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Wavecar.Gpoints)


                    * [`Wavecar.coeffs`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Wavecar.coeffs)


                    * [`Wavecar._generate_G_points()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Wavecar._generate_G_points)


                    * [`Wavecar._generate_nbmax()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Wavecar._generate_nbmax)


                    * [`Wavecar.evaluate_wavefunc()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Wavecar.evaluate_wavefunc)


                    * [`Wavecar.fft_mesh()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Wavecar.fft_mesh)


                    * [`Wavecar.get_parchg()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Wavecar.get_parchg)


                    * [`Wavecar.write_unks()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Wavecar.write_unks)


                * [`Waveder`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Waveder)


                    * [`Waveder.cder_real`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Waveder.cder_real)


                    * [`Waveder.cder_imag`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Waveder.cder_imag)


                    * [`Waveder.cder`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Waveder.cder)


                    * [`Waveder.cder_imag`](pymatgen.io.vasp.md#id9)


                    * [`Waveder.cder_real`](pymatgen.io.vasp.md#id10)


                    * [`Waveder.from_binary()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Waveder.from_binary)


                    * [`Waveder.from_formatted()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Waveder.from_formatted)


                    * [`Waveder.get_orbital_derivative_between_states()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Waveder.get_orbital_derivative_between_states)


                    * [`Waveder.nbands`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Waveder.nbands)


                    * [`Waveder.nkpoints`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Waveder.nkpoints)


                    * [`Waveder.nspin`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Waveder.nspin)


                * [`Xdatcar`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Xdatcar)


                    * [`Xdatcar.structures`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Xdatcar.structures)


                    * [`Xdatcar.comment`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Xdatcar.comment)


                    * [`Xdatcar.concatenate()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Xdatcar.concatenate)


                    * [`Xdatcar.get_str()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Xdatcar.get_str)


                    * [`Xdatcar.get_string()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Xdatcar.get_string)


                    * [`Xdatcar.natoms`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Xdatcar.natoms)


                    * [`Xdatcar.site_symbols`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Xdatcar.site_symbols)


                    * [`Xdatcar.write_file()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.Xdatcar.write_file)


                * [`_parse_from_incar()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs._parse_from_incar)


                * [`_parse_parameters()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs._parse_parameters)


                * [`_parse_v_parameters()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs._parse_v_parameters)


                * [`_parse_varray()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs._parse_varray)


                * [`_vasprun_float()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs._vasprun_float)


                * [`get_adjusted_fermi_level()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.get_adjusted_fermi_level)


                * [`get_band_structure_from_vasp_multiple_branches()`](pymatgen.io.vasp.md#pymatgen.io.vasp.outputs.get_band_structure_from_vasp_multiple_branches)


            * [pymatgen.io.vasp.sets module](pymatgen.io.vasp.md#module-pymatgen.io.vasp.sets)


                * [`BadInputSetWarning`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.BadInputSetWarning)


                * [`DictSet`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.DictSet)


                    * [`DictSet._abc_impl`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.DictSet._abc_impl)


                    * [`DictSet.calculate_ng()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.DictSet.calculate_ng)


                    * [`DictSet.estimate_nbands()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.DictSet.estimate_nbands)


                    * [`DictSet.incar`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.DictSet.incar)


                    * [`DictSet.kpoints`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.DictSet.kpoints)


                    * [`DictSet.nelect`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.DictSet.nelect)


                    * [`DictSet.poscar`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.DictSet.poscar)


                    * [`DictSet.potcar_functional`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.DictSet.potcar_functional)


                    * [`DictSet.structure`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.DictSet.structure)


                    * [`DictSet.write_input()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.DictSet.write_input)


                * [`LobsterSet`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.LobsterSet)


                    * [`LobsterSet._abc_impl`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.LobsterSet._abc_impl)


                    * [`LobsterSet._valid_potcars`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.LobsterSet._valid_potcars)


                    * [`LobsterSet.incar`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.LobsterSet.incar)


                    * [`LobsterSet.user_potcar_functional`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.LobsterSet.user_potcar_functional)


                * [`MITMDSet`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MITMDSet)


                    * [`MITMDSet._abc_impl`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MITMDSet._abc_impl)


                    * [`MITMDSet.kpoints`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MITMDSet.kpoints)


                    * [`MITMDSet.user_potcar_functional`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MITMDSet.user_potcar_functional)


                * [`MITNEBSet`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MITNEBSet)


                    * [`MITNEBSet._abc_impl`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MITNEBSet._abc_impl)


                    * [`MITNEBSet._process_structures()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MITNEBSet._process_structures)


                    * [`MITNEBSet.poscar`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MITNEBSet.poscar)


                    * [`MITNEBSet.poscars`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MITNEBSet.poscars)


                    * [`MITNEBSet.user_potcar_functional`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MITNEBSet.user_potcar_functional)


                    * [`MITNEBSet.write_input()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MITNEBSet.write_input)


                * [`MITRelaxSet`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MITRelaxSet)


                    * [`MITRelaxSet.CONFIG`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MITRelaxSet.CONFIG)


                    * [`MITRelaxSet._abc_impl`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MITRelaxSet._abc_impl)


                    * [`MITRelaxSet.user_potcar_functional`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MITRelaxSet.user_potcar_functional)


                * [`MPAbsorptionSet`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPAbsorptionSet)


                    * [`MPAbsorptionSet.SUPPORTED_MODES`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPAbsorptionSet.SUPPORTED_MODES)


                    * [`MPAbsorptionSet._abc_impl`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPAbsorptionSet._abc_impl)


                    * [`MPAbsorptionSet.from_prev_calc()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPAbsorptionSet.from_prev_calc)


                    * [`MPAbsorptionSet.incar`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPAbsorptionSet.incar)


                    * [`MPAbsorptionSet.kpoints`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPAbsorptionSet.kpoints)


                    * [`MPAbsorptionSet.override_from_prev_calc()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPAbsorptionSet.override_from_prev_calc)


                    * [`MPAbsorptionSet.user_potcar_functional`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPAbsorptionSet.user_potcar_functional)


                * [`MPHSEBSSet`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPHSEBSSet)


                    * [`MPHSEBSSet._abc_impl`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPHSEBSSet._abc_impl)


                    * [`MPHSEBSSet.from_prev_calc()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPHSEBSSet.from_prev_calc)


                    * [`MPHSEBSSet.kpoints`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPHSEBSSet.kpoints)


                    * [`MPHSEBSSet.override_from_prev_calc()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPHSEBSSet.override_from_prev_calc)


                    * [`MPHSEBSSet.user_potcar_functional`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPHSEBSSet.user_potcar_functional)


                * [`MPHSERelaxSet`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPHSERelaxSet)


                    * [`MPHSERelaxSet.CONFIG`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPHSERelaxSet.CONFIG)


                    * [`MPHSERelaxSet._abc_impl`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPHSERelaxSet._abc_impl)


                    * [`MPHSERelaxSet.user_potcar_functional`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPHSERelaxSet.user_potcar_functional)


                * [`MPMDSet`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPMDSet)


                    * [`MPMDSet._abc_impl`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPMDSet._abc_impl)


                    * [`MPMDSet.incar`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPMDSet.incar)


                    * [`MPMDSet.kpoints`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPMDSet.kpoints)


                    * [`MPMDSet.user_potcar_functional`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPMDSet.user_potcar_functional)


                * [`MPMetalRelaxSet`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPMetalRelaxSet)


                    * [`MPMetalRelaxSet._abc_impl`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPMetalRelaxSet._abc_impl)


                    * [`MPMetalRelaxSet.user_potcar_functional`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPMetalRelaxSet.user_potcar_functional)


                * [`MPNMRSet`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPNMRSet)


                    * [`MPNMRSet._abc_impl`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPNMRSet._abc_impl)


                    * [`MPNMRSet.incar`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPNMRSet.incar)


                    * [`MPNMRSet.user_potcar_functional`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPNMRSet.user_potcar_functional)


                * [`MPNonSCFSet`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPNonSCFSet)


                    * [`MPNonSCFSet._abc_impl`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPNonSCFSet._abc_impl)


                    * [`MPNonSCFSet.from_prev_calc()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPNonSCFSet.from_prev_calc)


                    * [`MPNonSCFSet.incar`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPNonSCFSet.incar)


                    * [`MPNonSCFSet.kpoints`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPNonSCFSet.kpoints)


                    * [`MPNonSCFSet.override_from_prev_calc()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPNonSCFSet.override_from_prev_calc)


                    * [`MPNonSCFSet.user_potcar_functional`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPNonSCFSet.user_potcar_functional)


                * [`MPRelaxSet`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPRelaxSet)


                    * [`MPRelaxSet.CONFIG`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPRelaxSet.CONFIG)


                    * [`MPRelaxSet._abc_impl`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPRelaxSet._abc_impl)


                    * [`MPRelaxSet.user_potcar_functional`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPRelaxSet.user_potcar_functional)


                * [`MPSOCSet`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPSOCSet)


                    * [`MPSOCSet._abc_impl`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPSOCSet._abc_impl)


                    * [`MPSOCSet.from_prev_calc()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPSOCSet.from_prev_calc)


                    * [`MPSOCSet.incar`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPSOCSet.incar)


                    * [`MPSOCSet.override_from_prev_calc()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPSOCSet.override_from_prev_calc)


                    * [`MPSOCSet.user_potcar_functional`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPSOCSet.user_potcar_functional)


                * [`MPScanRelaxSet`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPScanRelaxSet)


                    * [`MPScanRelaxSet.CONFIG`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPScanRelaxSet.CONFIG)


                    * [`MPScanRelaxSet._abc_impl`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPScanRelaxSet._abc_impl)


                    * [`MPScanRelaxSet._valid_potcars`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPScanRelaxSet._valid_potcars)


                    * [`MPScanRelaxSet.user_potcar_functional`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPScanRelaxSet.user_potcar_functional)


                * [`MPScanStaticSet`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPScanStaticSet)


                    * [`MPScanStaticSet._abc_impl`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPScanStaticSet._abc_impl)


                    * [`MPScanStaticSet.from_prev_calc()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPScanStaticSet.from_prev_calc)


                    * [`MPScanStaticSet.incar`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPScanStaticSet.incar)


                    * [`MPScanStaticSet.override_from_prev_calc()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPScanStaticSet.override_from_prev_calc)


                    * [`MPScanStaticSet.user_potcar_functional`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPScanStaticSet.user_potcar_functional)


                * [`MPStaticSet`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPStaticSet)


                    * [`MPStaticSet._abc_impl`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPStaticSet._abc_impl)


                    * [`MPStaticSet.from_prev_calc()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPStaticSet.from_prev_calc)


                    * [`MPStaticSet.incar`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPStaticSet.incar)


                    * [`MPStaticSet.kpoints`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPStaticSet.kpoints)


                    * [`MPStaticSet.override_from_prev_calc()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPStaticSet.override_from_prev_calc)


                    * [`MPStaticSet.user_potcar_functional`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MPStaticSet.user_potcar_functional)


                * [`MVLElasticSet`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLElasticSet)


                    * [`MVLElasticSet._abc_impl`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLElasticSet._abc_impl)


                    * [`MVLElasticSet.user_potcar_functional`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLElasticSet.user_potcar_functional)


                * [`MVLGBSet`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLGBSet)


                    * [`MVLGBSet._abc_impl`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLGBSet._abc_impl)


                    * [`MVLGBSet.incar`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLGBSet.incar)


                    * [`MVLGBSet.kpoints`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLGBSet.kpoints)


                    * [`MVLGBSet.user_potcar_functional`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLGBSet.user_potcar_functional)


                * [`MVLGWSet`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLGWSet)


                    * [`MVLGWSet.CONFIG`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLGWSet.CONFIG)


                    * [`MVLGWSet.SUPPORTED_MODES`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLGWSet.SUPPORTED_MODES)


                    * [`MVLGWSet._abc_impl`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLGWSet._abc_impl)


                    * [`MVLGWSet.from_prev_calc()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLGWSet.from_prev_calc)


                    * [`MVLGWSet.incar`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLGWSet.incar)


                    * [`MVLGWSet.kpoints`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLGWSet.kpoints)


                    * [`MVLGWSet.override_from_prev_calc()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLGWSet.override_from_prev_calc)


                    * [`MVLGWSet.user_potcar_functional`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLGWSet.user_potcar_functional)


                * [`MVLNPTMDSet`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLNPTMDSet)


                    * [`MVLNPTMDSet._abc_impl`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLNPTMDSet._abc_impl)


                    * [`MVLNPTMDSet.incar`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLNPTMDSet.incar)


                    * [`MVLNPTMDSet.user_potcar_functional`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLNPTMDSet.user_potcar_functional)


                * [`MVLRelax52Set`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLRelax52Set)


                    * [`MVLRelax52Set.CONFIG`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLRelax52Set.CONFIG)


                    * [`MVLRelax52Set._abc_impl`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLRelax52Set._abc_impl)


                    * [`MVLRelax52Set._valid_potcars`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLRelax52Set._valid_potcars)


                    * [`MVLRelax52Set.user_potcar_functional`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLRelax52Set.user_potcar_functional)


                * [`MVLScanRelaxSet`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLScanRelaxSet)


                    * [`MVLScanRelaxSet._abc_impl`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLScanRelaxSet._abc_impl)


                    * [`MVLScanRelaxSet._valid_potcars`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLScanRelaxSet._valid_potcars)


                    * [`MVLScanRelaxSet.user_potcar_functional`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLScanRelaxSet.user_potcar_functional)


                * [`MVLSlabSet`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLSlabSet)


                    * [`MVLSlabSet._abc_impl`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLSlabSet._abc_impl)


                    * [`MVLSlabSet.as_dict()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLSlabSet.as_dict)


                    * [`MVLSlabSet.incar`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLSlabSet.incar)


                    * [`MVLSlabSet.kpoints`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLSlabSet.kpoints)


                    * [`MVLSlabSet.user_potcar_functional`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MVLSlabSet.user_potcar_functional)


                * [`MatPESStaticSet`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MatPESStaticSet)


                    * [`MatPESStaticSet.CONFIG`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MatPESStaticSet.CONFIG)


                    * [`MatPESStaticSet.INHERITED_INCAR_PARAMS`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MatPESStaticSet.INHERITED_INCAR_PARAMS)


                    * [`MatPESStaticSet._abc_impl`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MatPESStaticSet._abc_impl)


                    * [`MatPESStaticSet.from_prev_calc()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MatPESStaticSet.from_prev_calc)


                    * [`MatPESStaticSet.incar`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MatPESStaticSet.incar)


                    * [`MatPESStaticSet.user_potcar_functional`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.MatPESStaticSet.user_potcar_functional)


                * [`VaspInputSet`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.VaspInputSet)


                    * [`VaspInputSet._abc_impl`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.VaspInputSet._abc_impl)


                    * [`VaspInputSet._valid_potcars`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.VaspInputSet._valid_potcars)


                    * [`VaspInputSet.as_dict()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.VaspInputSet.as_dict)


                    * [`VaspInputSet.get_vasp_input()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.VaspInputSet.get_vasp_input)


                    * [`VaspInputSet.incar`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.VaspInputSet.incar)


                    * [`VaspInputSet.kpoints`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.VaspInputSet.kpoints)


                    * [`VaspInputSet.poscar`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.VaspInputSet.poscar)


                    * [`VaspInputSet.potcar`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.VaspInputSet.potcar)


                    * [`VaspInputSet.potcar_symbols`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.VaspInputSet.potcar_symbols)


                    * [`VaspInputSet.write_input()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.VaspInputSet.write_input)


                * [`_load_yaml_config()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets._load_yaml_config)


                * [`batch_write_input()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.batch_write_input)


                * [`get_structure_from_prev_run()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.get_structure_from_prev_run)


                * [`get_valid_magmom_struct()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.get_valid_magmom_struct)


                * [`get_vasprun_outcar()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.get_vasprun_outcar)


                * [`next_num_with_prime_factors()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.next_num_with_prime_factors)


                * [`primes_less_than()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.primes_less_than)


                * [`standardize_structure()`](pymatgen.io.vasp.md#pymatgen.io.vasp.sets.standardize_structure)


        * [pymatgen.io.xtb package](pymatgen.io.xtb.md)




            * [pymatgen.io.xtb.inputs module](pymatgen.io.xtb.md#module-pymatgen.io.xtb.inputs)


                * [`CRESTInput`](pymatgen.io.xtb.md#pymatgen.io.xtb.inputs.CRESTInput)


                    * [`CRESTInput.constrains_template()`](pymatgen.io.xtb.md#pymatgen.io.xtb.inputs.CRESTInput.constrains_template)


                    * [`CRESTInput.write_input_files()`](pymatgen.io.xtb.md#pymatgen.io.xtb.inputs.CRESTInput.write_input_files)


            * [pymatgen.io.xtb.outputs module](pymatgen.io.xtb.md#module-pymatgen.io.xtb.outputs)


                * [`CRESTOutput`](pymatgen.io.xtb.md#pymatgen.io.xtb.outputs.CRESTOutput)


                    * [`CRESTOutput._parse_crest_output()`](pymatgen.io.xtb.md#pymatgen.io.xtb.outputs.CRESTOutput._parse_crest_output)




    * [pymatgen.io.adf module](pymatgen.io.md#module-pymatgen.io.adf)


        * [`AdfInput`](pymatgen.io.md#pymatgen.io.adf.AdfInput)


            * [`AdfInput.write_file()`](pymatgen.io.md#pymatgen.io.adf.AdfInput.write_file)


        * [`AdfInputError`](pymatgen.io.md#pymatgen.io.adf.AdfInputError)


        * [`AdfKey`](pymatgen.io.md#pymatgen.io.adf.AdfKey)


            * [`AdfKey._full_blocks`](pymatgen.io.md#pymatgen.io.adf.AdfKey._full_blocks)


            * [`AdfKey._options_string()`](pymatgen.io.md#pymatgen.io.adf.AdfKey._options_string)


            * [`AdfKey.add_option()`](pymatgen.io.md#pymatgen.io.adf.AdfKey.add_option)


            * [`AdfKey.add_subkey()`](pymatgen.io.md#pymatgen.io.adf.AdfKey.add_subkey)


            * [`AdfKey.as_dict()`](pymatgen.io.md#pymatgen.io.adf.AdfKey.as_dict)


            * [`AdfKey.block_keys`](pymatgen.io.md#pymatgen.io.adf.AdfKey.block_keys)


            * [`AdfKey.from_dict()`](pymatgen.io.md#pymatgen.io.adf.AdfKey.from_dict)


            * [`AdfKey.from_str()`](pymatgen.io.md#pymatgen.io.adf.AdfKey.from_str)


            * [`AdfKey.from_string()`](pymatgen.io.md#pymatgen.io.adf.AdfKey.from_string)


            * [`AdfKey.has_option()`](pymatgen.io.md#pymatgen.io.adf.AdfKey.has_option)


            * [`AdfKey.has_subkey()`](pymatgen.io.md#pymatgen.io.adf.AdfKey.has_subkey)


            * [`AdfKey.is_block_key()`](pymatgen.io.md#pymatgen.io.adf.AdfKey.is_block_key)


            * [`AdfKey.key`](pymatgen.io.md#pymatgen.io.adf.AdfKey.key)


            * [`AdfKey.remove_option()`](pymatgen.io.md#pymatgen.io.adf.AdfKey.remove_option)


            * [`AdfKey.remove_subkey()`](pymatgen.io.md#pymatgen.io.adf.AdfKey.remove_subkey)


            * [`AdfKey.sub_keys`](pymatgen.io.md#pymatgen.io.adf.AdfKey.sub_keys)


        * [`AdfOutput`](pymatgen.io.md#pymatgen.io.adf.AdfOutput)


            * [`AdfOutput._parse()`](pymatgen.io.md#pymatgen.io.adf.AdfOutput._parse)


            * [`AdfOutput._parse_adf_output()`](pymatgen.io.md#pymatgen.io.adf.AdfOutput._parse_adf_output)


            * [`AdfOutput._parse_logfile()`](pymatgen.io.md#pymatgen.io.adf.AdfOutput._parse_logfile)


            * [`AdfOutput._sites_to_mol()`](pymatgen.io.md#pymatgen.io.adf.AdfOutput._sites_to_mol)


        * [`AdfOutputError`](pymatgen.io.md#pymatgen.io.adf.AdfOutputError)


        * [`AdfTask`](pymatgen.io.md#pymatgen.io.adf.AdfTask)


            * [`AdfTask._setup_task()`](pymatgen.io.md#pymatgen.io.adf.AdfTask._setup_task)


            * [`AdfTask.as_dict()`](pymatgen.io.md#pymatgen.io.adf.AdfTask.as_dict)


            * [`AdfTask.from_dict()`](pymatgen.io.md#pymatgen.io.adf.AdfTask.from_dict)


            * [`AdfTask.get_default_basis_set()`](pymatgen.io.md#pymatgen.io.adf.AdfTask.get_default_basis_set)


            * [`AdfTask.get_default_geo()`](pymatgen.io.md#pymatgen.io.adf.AdfTask.get_default_geo)


            * [`AdfTask.get_default_scf()`](pymatgen.io.md#pymatgen.io.adf.AdfTask.get_default_scf)


            * [`AdfTask.get_default_units()`](pymatgen.io.md#pymatgen.io.adf.AdfTask.get_default_units)


            * [`AdfTask.get_default_xc()`](pymatgen.io.md#pymatgen.io.adf.AdfTask.get_default_xc)


            * [`AdfTask.operations`](pymatgen.io.md#pymatgen.io.adf.AdfTask.operations)


        * [`is_numeric()`](pymatgen.io.md#pymatgen.io.adf.is_numeric)


        * [`iterlines()`](pymatgen.io.md#pymatgen.io.adf.iterlines)


    * [pymatgen.io.ase module](pymatgen.io.md#module-pymatgen.io.ase)


        * [`AseAtomsAdaptor`](pymatgen.io.md#pymatgen.io.ase.AseAtomsAdaptor)


            * [`AseAtomsAdaptor.get_atoms()`](pymatgen.io.md#pymatgen.io.ase.AseAtomsAdaptor.get_atoms)


            * [`AseAtomsAdaptor.get_molecule()`](pymatgen.io.md#pymatgen.io.ase.AseAtomsAdaptor.get_molecule)


            * [`AseAtomsAdaptor.get_structure()`](pymatgen.io.md#pymatgen.io.ase.AseAtomsAdaptor.get_structure)


    * [pymatgen.io.atat module](pymatgen.io.md#module-pymatgen.io.atat)


        * [`Mcsqs`](pymatgen.io.md#pymatgen.io.atat.Mcsqs)


            * [`Mcsqs.structure_from_str()`](pymatgen.io.md#pymatgen.io.atat.Mcsqs.structure_from_str)


            * [`Mcsqs.structure_from_string()`](pymatgen.io.md#pymatgen.io.atat.Mcsqs.structure_from_string)


            * [`Mcsqs.to_str()`](pymatgen.io.md#pymatgen.io.atat.Mcsqs.to_str)


            * [`Mcsqs.to_string()`](pymatgen.io.md#pymatgen.io.atat.Mcsqs.to_string)


    * [pymatgen.io.babel module](pymatgen.io.md#module-pymatgen.io.babel)


        * [`BabelMolAdaptor`](pymatgen.io.md#pymatgen.io.babel.BabelMolAdaptor)


            * [`BabelMolAdaptor.add_hydrogen()`](pymatgen.io.md#pymatgen.io.babel.BabelMolAdaptor.add_hydrogen)


            * [`BabelMolAdaptor.confab_conformers()`](pymatgen.io.md#pymatgen.io.babel.BabelMolAdaptor.confab_conformers)


            * [`BabelMolAdaptor.from_file()`](pymatgen.io.md#pymatgen.io.babel.BabelMolAdaptor.from_file)


            * [`BabelMolAdaptor.from_molecule_graph()`](pymatgen.io.md#pymatgen.io.babel.BabelMolAdaptor.from_molecule_graph)


            * [`BabelMolAdaptor.from_str`](pymatgen.io.md#pymatgen.io.babel.BabelMolAdaptor.from_str)


            * [`BabelMolAdaptor.from_string()`](pymatgen.io.md#pymatgen.io.babel.BabelMolAdaptor.from_string)


            * [`BabelMolAdaptor.gen3d_conformer()`](pymatgen.io.md#pymatgen.io.babel.BabelMolAdaptor.gen3d_conformer)


            * [`BabelMolAdaptor.localopt()`](pymatgen.io.md#pymatgen.io.babel.BabelMolAdaptor.localopt)


            * [`BabelMolAdaptor.make3d()`](pymatgen.io.md#pymatgen.io.babel.BabelMolAdaptor.make3d)


            * [`BabelMolAdaptor.openbabel_mol`](pymatgen.io.md#pymatgen.io.babel.BabelMolAdaptor.openbabel_mol)


            * [`BabelMolAdaptor.pybel_mol`](pymatgen.io.md#pymatgen.io.babel.BabelMolAdaptor.pybel_mol)


            * [`BabelMolAdaptor.pymatgen_mol`](pymatgen.io.md#pymatgen.io.babel.BabelMolAdaptor.pymatgen_mol)


            * [`BabelMolAdaptor.remove_bond()`](pymatgen.io.md#pymatgen.io.babel.BabelMolAdaptor.remove_bond)


            * [`BabelMolAdaptor.rotor_conformer()`](pymatgen.io.md#pymatgen.io.babel.BabelMolAdaptor.rotor_conformer)


            * [`BabelMolAdaptor.write_file()`](pymatgen.io.md#pymatgen.io.babel.BabelMolAdaptor.write_file)


    * [pymatgen.io.cif module](pymatgen.io.md#module-pymatgen.io.cif)


        * [`CifBlock`](pymatgen.io.md#pymatgen.io.cif.CifBlock)


            * [`CifBlock._format_field()`](pymatgen.io.md#pymatgen.io.cif.CifBlock._format_field)


            * [`CifBlock._loop_to_string()`](pymatgen.io.md#pymatgen.io.cif.CifBlock._loop_to_string)


            * [`CifBlock._process_string()`](pymatgen.io.md#pymatgen.io.cif.CifBlock._process_string)


            * [`CifBlock.from_str()`](pymatgen.io.md#pymatgen.io.cif.CifBlock.from_str)


            * [`CifBlock.from_string()`](pymatgen.io.md#pymatgen.io.cif.CifBlock.from_string)


            * [`CifBlock.maxlen`](pymatgen.io.md#pymatgen.io.cif.CifBlock.maxlen)


        * [`CifFile`](pymatgen.io.md#pymatgen.io.cif.CifFile)


            * [`CifFile.from_file()`](pymatgen.io.md#pymatgen.io.cif.CifFile.from_file)


            * [`CifFile.from_str()`](pymatgen.io.md#pymatgen.io.cif.CifFile.from_str)


            * [`CifFile.from_string()`](pymatgen.io.md#pymatgen.io.cif.CifFile.from_string)


        * [`CifParser`](pymatgen.io.md#pymatgen.io.cif.CifParser)


            * [`CifParser._get_structure()`](pymatgen.io.md#pymatgen.io.cif.CifParser._get_structure)


            * [`CifParser._parse_symbol()`](pymatgen.io.md#pymatgen.io.cif.CifParser._parse_symbol)


            * [`CifParser._sanitize_data()`](pymatgen.io.md#pymatgen.io.cif.CifParser._sanitize_data)


            * [`CifParser._unique_coords()`](pymatgen.io.md#pymatgen.io.cif.CifParser._unique_coords)


            * [`CifParser.as_dict()`](pymatgen.io.md#pymatgen.io.cif.CifParser.as_dict)


            * [`CifParser.from_str()`](pymatgen.io.md#pymatgen.io.cif.CifParser.from_str)


            * [`CifParser.from_string()`](pymatgen.io.md#pymatgen.io.cif.CifParser.from_string)


            * [`CifParser.get_bibtex_string()`](pymatgen.io.md#pymatgen.io.cif.CifParser.get_bibtex_string)


            * [`CifParser.get_lattice()`](pymatgen.io.md#pymatgen.io.cif.CifParser.get_lattice)


            * [`CifParser.get_lattice_no_exception()`](pymatgen.io.md#pymatgen.io.cif.CifParser.get_lattice_no_exception)


            * [`CifParser.get_magsymops()`](pymatgen.io.md#pymatgen.io.cif.CifParser.get_magsymops)


            * [`CifParser.get_structures()`](pymatgen.io.md#pymatgen.io.cif.CifParser.get_structures)


            * [`CifParser.get_symops()`](pymatgen.io.md#pymatgen.io.cif.CifParser.get_symops)


            * [`CifParser.has_errors`](pymatgen.io.md#pymatgen.io.cif.CifParser.has_errors)


            * [`CifParser.parse_magmoms()`](pymatgen.io.md#pymatgen.io.cif.CifParser.parse_magmoms)


            * [`CifParser.parse_oxi_states()`](pymatgen.io.md#pymatgen.io.cif.CifParser.parse_oxi_states)


        * [`CifWriter`](pymatgen.io.md#pymatgen.io.cif.CifWriter)


            * [`CifWriter.ciffile`](pymatgen.io.md#pymatgen.io.cif.CifWriter.ciffile)


            * [`CifWriter.write_file()`](pymatgen.io.md#pymatgen.io.cif.CifWriter.write_file)


        * [`str2float()`](pymatgen.io.md#pymatgen.io.cif.str2float)


    * [pymatgen.io.common module](pymatgen.io.md#module-pymatgen.io.common)


        * [`VolumetricData`](pymatgen.io.md#pymatgen.io.common.VolumetricData)


            * [`VolumetricData.structure`](pymatgen.io.md#pymatgen.io.common.VolumetricData.structure)


            * [`VolumetricData.is_spin_polarized`](pymatgen.io.md#pymatgen.io.common.VolumetricData.is_spin_polarized)


            * [`VolumetricData.dim`](pymatgen.io.md#pymatgen.io.common.VolumetricData.dim)


            * [`VolumetricData.data`](pymatgen.io.md#pymatgen.io.common.VolumetricData.data)


            * [`VolumetricData.ngridpts`](pymatgen.io.md#pymatgen.io.common.VolumetricData.ngridpts)


            * [`VolumetricData.copy()`](pymatgen.io.md#pymatgen.io.common.VolumetricData.copy)


            * [`VolumetricData.from_cube()`](pymatgen.io.md#pymatgen.io.common.VolumetricData.from_cube)


            * [`VolumetricData.from_hdf5()`](pymatgen.io.md#pymatgen.io.common.VolumetricData.from_hdf5)


            * [`VolumetricData.get_average_along_axis()`](pymatgen.io.md#pymatgen.io.common.VolumetricData.get_average_along_axis)


            * [`VolumetricData.get_axis_grid()`](pymatgen.io.md#pymatgen.io.common.VolumetricData.get_axis_grid)


            * [`VolumetricData.get_integrated_diff()`](pymatgen.io.md#pymatgen.io.common.VolumetricData.get_integrated_diff)


            * [`VolumetricData.linear_add()`](pymatgen.io.md#pymatgen.io.common.VolumetricData.linear_add)


            * [`VolumetricData.linear_slice()`](pymatgen.io.md#pymatgen.io.common.VolumetricData.linear_slice)


            * [`VolumetricData.scale()`](pymatgen.io.md#pymatgen.io.common.VolumetricData.scale)


            * [`VolumetricData.spin_data`](pymatgen.io.md#pymatgen.io.common.VolumetricData.spin_data)


            * [`VolumetricData.to_cube()`](pymatgen.io.md#pymatgen.io.common.VolumetricData.to_cube)


            * [`VolumetricData.to_hdf5()`](pymatgen.io.md#pymatgen.io.common.VolumetricData.to_hdf5)


            * [`VolumetricData.value_at()`](pymatgen.io.md#pymatgen.io.common.VolumetricData.value_at)


    * [pymatgen.io.core module](pymatgen.io.md#module-pymatgen.io.core)


        * [`InputFile`](pymatgen.io.md#pymatgen.io.core.InputFile)


            * [`InputFile.from_file()`](pymatgen.io.md#pymatgen.io.core.InputFile.from_file)


            * [`InputFile.from_str()`](pymatgen.io.md#pymatgen.io.core.InputFile.from_str)


            * [`InputFile.from_string()`](pymatgen.io.md#pymatgen.io.core.InputFile.from_string)


            * [`InputFile.get_str()`](pymatgen.io.md#pymatgen.io.core.InputFile.get_str)


            * [`InputFile.get_string()`](pymatgen.io.md#pymatgen.io.core.InputFile.get_string)


            * [`InputFile.write_file()`](pymatgen.io.md#pymatgen.io.core.InputFile.write_file)


        * [`InputGenerator`](pymatgen.io.md#pymatgen.io.core.InputGenerator)


            * [`InputGenerator.get_input_set()`](pymatgen.io.md#pymatgen.io.core.InputGenerator.get_input_set)


        * [`InputSet`](pymatgen.io.md#pymatgen.io.core.InputSet)


            * [`InputSet._abc_impl`](pymatgen.io.md#pymatgen.io.core.InputSet._abc_impl)


            * [`InputSet.from_directory()`](pymatgen.io.md#pymatgen.io.core.InputSet.from_directory)


            * [`InputSet.validate()`](pymatgen.io.md#pymatgen.io.core.InputSet.validate)


            * [`InputSet.write_input()`](pymatgen.io.md#pymatgen.io.core.InputSet.write_input)


        * [`ParseError`](pymatgen.io.md#pymatgen.io.core.ParseError)


    * [pymatgen.io.cssr module](pymatgen.io.md#module-pymatgen.io.cssr)


        * [`Cssr`](pymatgen.io.md#pymatgen.io.cssr.Cssr)


            * [`Cssr.from_file()`](pymatgen.io.md#pymatgen.io.cssr.Cssr.from_file)


            * [`Cssr.from_str()`](pymatgen.io.md#pymatgen.io.cssr.Cssr.from_str)


            * [`Cssr.write_file()`](pymatgen.io.md#pymatgen.io.cssr.Cssr.write_file)


    * [pymatgen.io.fiesta module](pymatgen.io.md#module-pymatgen.io.fiesta)


        * [`BSEOutput`](pymatgen.io.md#pymatgen.io.fiesta.BSEOutput)


            * [`BSEOutput._parse_job()`](pymatgen.io.md#pymatgen.io.fiesta.BSEOutput._parse_job)


        * [`BasisSetReader`](pymatgen.io.md#pymatgen.io.fiesta.BasisSetReader)


            * [`BasisSetReader._parse_file()`](pymatgen.io.md#pymatgen.io.fiesta.BasisSetReader._parse_file)


            * [`BasisSetReader.infos_on_basis_set()`](pymatgen.io.md#pymatgen.io.fiesta.BasisSetReader.infos_on_basis_set)


            * [`BasisSetReader.set_n_nlmo()`](pymatgen.io.md#pymatgen.io.fiesta.BasisSetReader.set_n_nlmo)


        * [`FiestaInput`](pymatgen.io.md#pymatgen.io.fiesta.FiestaInput)


            * [`FiestaInput.as_dict()`](pymatgen.io.md#pymatgen.io.fiesta.FiestaInput.as_dict)


            * [`FiestaInput.dump_BSE_data_in_GW_run()`](pymatgen.io.md#pymatgen.io.fiesta.FiestaInput.dump_BSE_data_in_GW_run)


            * [`FiestaInput.dump_TDDFT_data_in_GW_run()`](pymatgen.io.md#pymatgen.io.fiesta.FiestaInput.dump_TDDFT_data_in_GW_run)


            * [`FiestaInput.from_dict()`](pymatgen.io.md#pymatgen.io.fiesta.FiestaInput.from_dict)


            * [`FiestaInput.from_file()`](pymatgen.io.md#pymatgen.io.fiesta.FiestaInput.from_file)


            * [`FiestaInput.from_str()`](pymatgen.io.md#pymatgen.io.fiesta.FiestaInput.from_str)


            * [`FiestaInput.from_string()`](pymatgen.io.md#pymatgen.io.fiesta.FiestaInput.from_string)


            * [`FiestaInput.infos_on_system`](pymatgen.io.md#pymatgen.io.fiesta.FiestaInput.infos_on_system)


            * [`FiestaInput.make_FULL_BSE_Densities_folder()`](pymatgen.io.md#pymatgen.io.fiesta.FiestaInput.make_FULL_BSE_Densities_folder)


            * [`FiestaInput.molecule`](pymatgen.io.md#pymatgen.io.fiesta.FiestaInput.molecule)


            * [`FiestaInput.set_BSE_options()`](pymatgen.io.md#pymatgen.io.fiesta.FiestaInput.set_BSE_options)


            * [`FiestaInput.set_GW_options()`](pymatgen.io.md#pymatgen.io.fiesta.FiestaInput.set_GW_options)


            * [`FiestaInput.set_auxiliary_basis_set()`](pymatgen.io.md#pymatgen.io.fiesta.FiestaInput.set_auxiliary_basis_set)


            * [`FiestaInput.write_file()`](pymatgen.io.md#pymatgen.io.fiesta.FiestaInput.write_file)


        * [`FiestaOutput`](pymatgen.io.md#pymatgen.io.fiesta.FiestaOutput)


            * [`FiestaOutput._parse_job()`](pymatgen.io.md#pymatgen.io.fiesta.FiestaOutput._parse_job)


        * [`FiestaRun`](pymatgen.io.md#pymatgen.io.fiesta.FiestaRun)


            * [`FiestaRun._gw_run()`](pymatgen.io.md#pymatgen.io.fiesta.FiestaRun._gw_run)


            * [`FiestaRun.as_dict()`](pymatgen.io.md#pymatgen.io.fiesta.FiestaRun.as_dict)


            * [`FiestaRun.bse_run()`](pymatgen.io.md#pymatgen.io.fiesta.FiestaRun.bse_run)


            * [`FiestaRun.from_dict()`](pymatgen.io.md#pymatgen.io.fiesta.FiestaRun.from_dict)


            * [`FiestaRun.run()`](pymatgen.io.md#pymatgen.io.fiesta.FiestaRun.run)


        * [`Nwchem2Fiesta`](pymatgen.io.md#pymatgen.io.fiesta.Nwchem2Fiesta)


            * [`Nwchem2Fiesta.as_dict()`](pymatgen.io.md#pymatgen.io.fiesta.Nwchem2Fiesta.as_dict)


            * [`Nwchem2Fiesta.from_dict()`](pymatgen.io.md#pymatgen.io.fiesta.Nwchem2Fiesta.from_dict)


            * [`Nwchem2Fiesta.run()`](pymatgen.io.md#pymatgen.io.fiesta.Nwchem2Fiesta.run)


    * [pymatgen.io.gaussian module](pymatgen.io.md#module-pymatgen.io.gaussian)


        * [`GaussianInput`](pymatgen.io.md#pymatgen.io.gaussian.GaussianInput)


            * [`GaussianInput._parse_coords()`](pymatgen.io.md#pymatgen.io.gaussian.GaussianInput._parse_coords)


            * [`GaussianInput._xyz_patt`](pymatgen.io.md#pymatgen.io.gaussian.GaussianInput._xyz_patt)


            * [`GaussianInput._zmat_patt`](pymatgen.io.md#pymatgen.io.gaussian.GaussianInput._zmat_patt)


            * [`GaussianInput.as_dict()`](pymatgen.io.md#pymatgen.io.gaussian.GaussianInput.as_dict)


            * [`GaussianInput.from_dict()`](pymatgen.io.md#pymatgen.io.gaussian.GaussianInput.from_dict)


            * [`GaussianInput.from_file()`](pymatgen.io.md#pymatgen.io.gaussian.GaussianInput.from_file)


            * [`GaussianInput.from_str()`](pymatgen.io.md#pymatgen.io.gaussian.GaussianInput.from_str)


            * [`GaussianInput.from_string()`](pymatgen.io.md#pymatgen.io.gaussian.GaussianInput.from_string)


            * [`GaussianInput.get_cart_coords()`](pymatgen.io.md#pymatgen.io.gaussian.GaussianInput.get_cart_coords)


            * [`GaussianInput.get_zmatrix()`](pymatgen.io.md#pymatgen.io.gaussian.GaussianInput.get_zmatrix)


            * [`GaussianInput.molecule`](pymatgen.io.md#pymatgen.io.gaussian.GaussianInput.molecule)


            * [`GaussianInput.to_str()`](pymatgen.io.md#pymatgen.io.gaussian.GaussianInput.to_str)


            * [`GaussianInput.to_string()`](pymatgen.io.md#pymatgen.io.gaussian.GaussianInput.to_string)


            * [`GaussianInput.write_file()`](pymatgen.io.md#pymatgen.io.gaussian.GaussianInput.write_file)


        * [`GaussianOutput`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput)


            * [`GaussianOutput.structures`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.structures)


            * [`GaussianOutput.structures_input_orientation`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.structures_input_orientation)


            * [`GaussianOutput.opt_structures`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.opt_structures)


            * [`GaussianOutput.energies`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.energies)


            * [`GaussianOutput.eigenvalues`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.eigenvalues)


            * [`GaussianOutput.MO_coefficients`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.MO_coefficients)


            * [`GaussianOutput.cart_forces`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.cart_forces)


            * [`GaussianOutput.frequencies`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.frequencies)


            * [`GaussianOutput.hessian`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.hessian)


            * [`GaussianOutput.properly_terminated`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.properly_terminated)


            * [`GaussianOutput.is_pcm`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.is_pcm)


            * [`GaussianOutput.is_spin`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.is_spin)


            * [`GaussianOutput.stationary_type`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.stationary_type)


            * [`GaussianOutput.corrections`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.corrections)


            * [`GaussianOutput.functional`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.functional)


            * [`GaussianOutput.basis_set`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.basis_set)


            * [`GaussianOutput.route`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.route)


            * [`GaussianOutput.dieze_tag`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.dieze_tag)


            * [`GaussianOutput.link0`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.link0)


            * [`GaussianOutput.charge`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.charge)


            * [`GaussianOutput.spin_multiplicity`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.spin_multiplicity)


            * [`GaussianOutput.num_basis_func`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.num_basis_func)


            * [`GaussianOutput.electrons`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.electrons)


            * [`GaussianOutput.pcm`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.pcm)


            * [`GaussianOutput.errors`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.errors)


            * [`GaussianOutput.Mulliken_charges`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.Mulliken_charges)


            * [`GaussianOutput.eigenvectors`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.eigenvectors)


            * [`GaussianOutput.molecular_orbital`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.molecular_orbital)


            * [`GaussianOutput.atom_basis_labels`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.atom_basis_labels)


            * [`GaussianOutput.resumes`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.resumes)


            * [`GaussianOutput.title`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.title)


            * [`GaussianOutput.standard_orientation`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.standard_orientation)


            * [`GaussianOutput.bond_orders`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.bond_orders)


            * [`GaussianOutput.read_scan()`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.read_scan)


            * [`GaussianOutput.get_scan_plot()`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.get_scan_plot)


            * [`GaussianOutput.save_scan_plot()`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.save_scan_plot)


            * [`GaussianOutput._check_pcm()`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput._check_pcm)


            * [`GaussianOutput._parse()`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput._parse)


            * [`GaussianOutput._parse_hessian()`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput._parse_hessian)


            * [`GaussianOutput.as_dict()`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.as_dict)


            * [`GaussianOutput.final_energy`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.final_energy)


            * [`GaussianOutput.final_structure`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.final_structure)


            * [`GaussianOutput.get_scan_plot()`](pymatgen.io.md#id0)


            * [`GaussianOutput.get_spectre_plot()`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.get_spectre_plot)


            * [`GaussianOutput.read_excitation_energies()`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.read_excitation_energies)


            * [`GaussianOutput.read_scan()`](pymatgen.io.md#id1)


            * [`GaussianOutput.save_scan_plot()`](pymatgen.io.md#id2)


            * [`GaussianOutput.save_spectre_plot()`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.save_spectre_plot)


            * [`GaussianOutput.to_input()`](pymatgen.io.md#pymatgen.io.gaussian.GaussianOutput.to_input)


        * [`read_route_line()`](pymatgen.io.md#pymatgen.io.gaussian.read_route_line)


    * [pymatgen.io.jarvis module](pymatgen.io.md#module-pymatgen.io.jarvis)


        * [`JarvisAtomsAdaptor`](pymatgen.io.md#pymatgen.io.jarvis.JarvisAtomsAdaptor)


            * [`JarvisAtomsAdaptor.get_atoms()`](pymatgen.io.md#pymatgen.io.jarvis.JarvisAtomsAdaptor.get_atoms)


            * [`JarvisAtomsAdaptor.get_structure()`](pymatgen.io.md#pymatgen.io.jarvis.JarvisAtomsAdaptor.get_structure)


    * [pymatgen.io.lmto module](pymatgen.io.md#module-pymatgen.io.lmto)


        * [`LMTOCopl`](pymatgen.io.md#pymatgen.io.lmto.LMTOCopl)


            * [`LMTOCopl.cohp_data`](pymatgen.io.md#pymatgen.io.lmto.LMTOCopl.cohp_data)


            * [`LMTOCopl.efermi`](pymatgen.io.md#pymatgen.io.lmto.LMTOCopl.efermi)


            * [`LMTOCopl.energies`](pymatgen.io.md#pymatgen.io.lmto.LMTOCopl.energies)


            * [`LMTOCopl.is_spin_polarized`](pymatgen.io.md#pymatgen.io.lmto.LMTOCopl.is_spin_polarized)


            * [`LMTOCopl._get_bond_data()`](pymatgen.io.md#pymatgen.io.lmto.LMTOCopl._get_bond_data)


        * [`LMTOCtrl`](pymatgen.io.md#pymatgen.io.lmto.LMTOCtrl)


            * [`LMTOCtrl.as_dict()`](pymatgen.io.md#pymatgen.io.lmto.LMTOCtrl.as_dict)


            * [`LMTOCtrl.from_dict()`](pymatgen.io.md#pymatgen.io.lmto.LMTOCtrl.from_dict)


            * [`LMTOCtrl.from_file()`](pymatgen.io.md#pymatgen.io.lmto.LMTOCtrl.from_file)


            * [`LMTOCtrl.from_str()`](pymatgen.io.md#pymatgen.io.lmto.LMTOCtrl.from_str)


            * [`LMTOCtrl.from_string()`](pymatgen.io.md#pymatgen.io.lmto.LMTOCtrl.from_string)


            * [`LMTOCtrl.get_str()`](pymatgen.io.md#pymatgen.io.lmto.LMTOCtrl.get_str)


            * [`LMTOCtrl.get_string()`](pymatgen.io.md#pymatgen.io.lmto.LMTOCtrl.get_string)


            * [`LMTOCtrl.write_file()`](pymatgen.io.md#pymatgen.io.lmto.LMTOCtrl.write_file)


    * [pymatgen.io.nwchem module](pymatgen.io.md#module-pymatgen.io.nwchem)


        * [`NwInput`](pymatgen.io.md#pymatgen.io.nwchem.NwInput)


            * [`NwInput.as_dict()`](pymatgen.io.md#pymatgen.io.nwchem.NwInput.as_dict)


            * [`NwInput.from_dict()`](pymatgen.io.md#pymatgen.io.nwchem.NwInput.from_dict)


            * [`NwInput.from_file()`](pymatgen.io.md#pymatgen.io.nwchem.NwInput.from_file)


            * [`NwInput.from_str()`](pymatgen.io.md#pymatgen.io.nwchem.NwInput.from_str)


            * [`NwInput.from_string()`](pymatgen.io.md#pymatgen.io.nwchem.NwInput.from_string)


            * [`NwInput.molecule`](pymatgen.io.md#pymatgen.io.nwchem.NwInput.molecule)


            * [`NwInput.write_file()`](pymatgen.io.md#pymatgen.io.nwchem.NwInput.write_file)


        * [`NwInputError`](pymatgen.io.md#pymatgen.io.nwchem.NwInputError)


        * [`NwOutput`](pymatgen.io.md#pymatgen.io.nwchem.NwOutput)


            * [`NwOutput._parse_job()`](pymatgen.io.md#pymatgen.io.nwchem.NwOutput._parse_job)


            * [`NwOutput._parse_preamble()`](pymatgen.io.md#pymatgen.io.nwchem.NwOutput._parse_preamble)


            * [`NwOutput.get_excitation_spectrum()`](pymatgen.io.md#pymatgen.io.nwchem.NwOutput.get_excitation_spectrum)


            * [`NwOutput.parse_tddft()`](pymatgen.io.md#pymatgen.io.nwchem.NwOutput.parse_tddft)


        * [`NwTask`](pymatgen.io.md#pymatgen.io.nwchem.NwTask)


            * [`NwTask.as_dict()`](pymatgen.io.md#pymatgen.io.nwchem.NwTask.as_dict)


            * [`NwTask.dft_task()`](pymatgen.io.md#pymatgen.io.nwchem.NwTask.dft_task)


            * [`NwTask.esp_task()`](pymatgen.io.md#pymatgen.io.nwchem.NwTask.esp_task)


            * [`NwTask.from_dict()`](pymatgen.io.md#pymatgen.io.nwchem.NwTask.from_dict)


            * [`NwTask.from_molecule()`](pymatgen.io.md#pymatgen.io.nwchem.NwTask.from_molecule)


            * [`NwTask.operations`](pymatgen.io.md#pymatgen.io.nwchem.NwTask.operations)


            * [`NwTask.theories`](pymatgen.io.md#pymatgen.io.nwchem.NwTask.theories)


    * [pymatgen.io.packmol module](pymatgen.io.md#module-pymatgen.io.packmol)


        * [`PackmolBoxGen`](pymatgen.io.md#pymatgen.io.packmol.PackmolBoxGen)


            * [`PackmolBoxGen.get_input_set()`](pymatgen.io.md#pymatgen.io.packmol.PackmolBoxGen.get_input_set)


        * [`PackmolSet`](pymatgen.io.md#pymatgen.io.packmol.PackmolSet)


            * [`PackmolSet._abc_impl`](pymatgen.io.md#pymatgen.io.packmol.PackmolSet._abc_impl)


            * [`PackmolSet.from_directory()`](pymatgen.io.md#pymatgen.io.packmol.PackmolSet.from_directory)


            * [`PackmolSet.run()`](pymatgen.io.md#pymatgen.io.packmol.PackmolSet.run)


    * [pymatgen.io.phonopy module](pymatgen.io.md#module-pymatgen.io.phonopy)


        * [`_extrapolate_grun()`](pymatgen.io.md#pymatgen.io.phonopy._extrapolate_grun)


        * [`eigvec_to_eigdispl()`](pymatgen.io.md#pymatgen.io.phonopy.eigvec_to_eigdispl)


        * [`get_complete_ph_dos()`](pymatgen.io.md#pymatgen.io.phonopy.get_complete_ph_dos)


        * [`get_displaced_structures()`](pymatgen.io.md#pymatgen.io.phonopy.get_displaced_structures)


        * [`get_gruneisen_ph_bs_symm_line()`](pymatgen.io.md#pymatgen.io.phonopy.get_gruneisen_ph_bs_symm_line)


        * [`get_gruneisenparameter()`](pymatgen.io.md#pymatgen.io.phonopy.get_gruneisenparameter)


        * [`get_gs_ph_bs_symm_line_from_dict()`](pymatgen.io.md#pymatgen.io.phonopy.get_gs_ph_bs_symm_line_from_dict)


        * [`get_ph_bs_symm_line()`](pymatgen.io.md#pymatgen.io.phonopy.get_ph_bs_symm_line)


        * [`get_ph_bs_symm_line_from_dict()`](pymatgen.io.md#pymatgen.io.phonopy.get_ph_bs_symm_line_from_dict)


        * [`get_ph_dos()`](pymatgen.io.md#pymatgen.io.phonopy.get_ph_dos)


        * [`get_phonon_band_structure_from_fc()`](pymatgen.io.md#pymatgen.io.phonopy.get_phonon_band_structure_from_fc)


        * [`get_phonon_band_structure_symm_line_from_fc()`](pymatgen.io.md#pymatgen.io.phonopy.get_phonon_band_structure_symm_line_from_fc)


        * [`get_phonon_dos_from_fc()`](pymatgen.io.md#pymatgen.io.phonopy.get_phonon_dos_from_fc)


        * [`get_phonopy_structure()`](pymatgen.io.md#pymatgen.io.phonopy.get_phonopy_structure)


        * [`get_pmg_structure()`](pymatgen.io.md#pymatgen.io.phonopy.get_pmg_structure)


        * [`get_structure_from_dict()`](pymatgen.io.md#pymatgen.io.phonopy.get_structure_from_dict)


        * [`get_thermal_displacement_matrices()`](pymatgen.io.md#pymatgen.io.phonopy.get_thermal_displacement_matrices)


    * [pymatgen.io.prismatic module](pymatgen.io.md#module-pymatgen.io.prismatic)


        * [`Prismatic`](pymatgen.io.md#pymatgen.io.prismatic.Prismatic)


            * [`Prismatic.to_str()`](pymatgen.io.md#pymatgen.io.prismatic.Prismatic.to_str)


            * [`Prismatic.to_string()`](pymatgen.io.md#pymatgen.io.prismatic.Prismatic.to_string)


    * [pymatgen.io.pwscf module](pymatgen.io.md#module-pymatgen.io.pwscf)


        * [`PWInput`](pymatgen.io.md#pymatgen.io.pwscf.PWInput)


            * [`PWInput.as_dict()`](pymatgen.io.md#pymatgen.io.pwscf.PWInput.as_dict)


            * [`PWInput.from_dict()`](pymatgen.io.md#pymatgen.io.pwscf.PWInput.from_dict)


            * [`PWInput.from_file()`](pymatgen.io.md#pymatgen.io.pwscf.PWInput.from_file)


            * [`PWInput.from_str()`](pymatgen.io.md#pymatgen.io.pwscf.PWInput.from_str)


            * [`PWInput.from_string()`](pymatgen.io.md#pymatgen.io.pwscf.PWInput.from_string)


            * [`PWInput.proc_val()`](pymatgen.io.md#pymatgen.io.pwscf.PWInput.proc_val)


            * [`PWInput.write_file()`](pymatgen.io.md#pymatgen.io.pwscf.PWInput.write_file)


        * [`PWInputError`](pymatgen.io.md#pymatgen.io.pwscf.PWInputError)


        * [`PWOutput`](pymatgen.io.md#pymatgen.io.pwscf.PWOutput)


            * [`PWOutput.final_energy`](pymatgen.io.md#pymatgen.io.pwscf.PWOutput.final_energy)


            * [`PWOutput.get_celldm()`](pymatgen.io.md#pymatgen.io.pwscf.PWOutput.get_celldm)


            * [`PWOutput.lattice_type`](pymatgen.io.md#pymatgen.io.pwscf.PWOutput.lattice_type)


            * [`PWOutput.patterns`](pymatgen.io.md#pymatgen.io.pwscf.PWOutput.patterns)


            * [`PWOutput.read_pattern()`](pymatgen.io.md#pymatgen.io.pwscf.PWOutput.read_pattern)


    * [pymatgen.io.res module](pymatgen.io.md#module-pymatgen.io.res)


        * [`AirssProvider`](pymatgen.io.md#pymatgen.io.res.AirssProvider)


            * [`AirssProvider._date_fmt`](pymatgen.io.md#pymatgen.io.res.AirssProvider._date_fmt)


            * [`AirssProvider._get_compile_options()`](pymatgen.io.md#pymatgen.io.res.AirssProvider._get_compile_options)


            * [`AirssProvider._get_compiler()`](pymatgen.io.md#pymatgen.io.res.AirssProvider._get_compiler)


            * [`AirssProvider._get_rng_seeds()`](pymatgen.io.md#pymatgen.io.res.AirssProvider._get_rng_seeds)


            * [`AirssProvider._parse_date()`](pymatgen.io.md#pymatgen.io.res.AirssProvider._parse_date)


            * [`AirssProvider._raise_or_none()`](pymatgen.io.md#pymatgen.io.res.AirssProvider._raise_or_none)


            * [`AirssProvider.appearances`](pymatgen.io.md#pymatgen.io.res.AirssProvider.appearances)


            * [`AirssProvider.as_dict()`](pymatgen.io.md#pymatgen.io.res.AirssProvider.as_dict)


            * [`AirssProvider.energy`](pymatgen.io.md#pymatgen.io.res.AirssProvider.energy)


            * [`AirssProvider.entry`](pymatgen.io.md#pymatgen.io.res.AirssProvider.entry)


            * [`AirssProvider.from_file()`](pymatgen.io.md#pymatgen.io.res.AirssProvider.from_file)


            * [`AirssProvider.from_str()`](pymatgen.io.md#pymatgen.io.res.AirssProvider.from_str)


            * [`AirssProvider.get_airss_version()`](pymatgen.io.md#pymatgen.io.res.AirssProvider.get_airss_version)


            * [`AirssProvider.get_castep_version()`](pymatgen.io.md#pymatgen.io.res.AirssProvider.get_castep_version)


            * [`AirssProvider.get_cut_grid_gmax_fsbc()`](pymatgen.io.md#pymatgen.io.res.AirssProvider.get_cut_grid_gmax_fsbc)


            * [`AirssProvider.get_func_rel_disp()`](pymatgen.io.md#pymatgen.io.res.AirssProvider.get_func_rel_disp)


            * [`AirssProvider.get_mpgrid_offset_nkpts_spacing()`](pymatgen.io.md#pymatgen.io.res.AirssProvider.get_mpgrid_offset_nkpts_spacing)


            * [`AirssProvider.get_pspots()`](pymatgen.io.md#pymatgen.io.res.AirssProvider.get_pspots)


            * [`AirssProvider.get_run_start_info()`](pymatgen.io.md#pymatgen.io.res.AirssProvider.get_run_start_info)


            * [`AirssProvider.integrated_absolute_spin_density`](pymatgen.io.md#pymatgen.io.res.AirssProvider.integrated_absolute_spin_density)


            * [`AirssProvider.integrated_spin_density`](pymatgen.io.md#pymatgen.io.res.AirssProvider.integrated_spin_density)


            * [`AirssProvider.pressure`](pymatgen.io.md#pymatgen.io.res.AirssProvider.pressure)


            * [`AirssProvider.seed`](pymatgen.io.md#pymatgen.io.res.AirssProvider.seed)


            * [`AirssProvider.spacegroup_label`](pymatgen.io.md#pymatgen.io.res.AirssProvider.spacegroup_label)


            * [`AirssProvider.volume`](pymatgen.io.md#pymatgen.io.res.AirssProvider.volume)


        * [`AirssTITL`](pymatgen.io.md#pymatgen.io.res.AirssTITL)


            * [`AirssTITL.appearances`](pymatgen.io.md#pymatgen.io.res.AirssTITL.appearances)


            * [`AirssTITL.energy`](pymatgen.io.md#pymatgen.io.res.AirssTITL.energy)


            * [`AirssTITL.integrated_absolute_spin_density`](pymatgen.io.md#pymatgen.io.res.AirssTITL.integrated_absolute_spin_density)


            * [`AirssTITL.integrated_spin_density`](pymatgen.io.md#pymatgen.io.res.AirssTITL.integrated_spin_density)


            * [`AirssTITL.pressure`](pymatgen.io.md#pymatgen.io.res.AirssTITL.pressure)


            * [`AirssTITL.seed`](pymatgen.io.md#pymatgen.io.res.AirssTITL.seed)


            * [`AirssTITL.spacegroup_label`](pymatgen.io.md#pymatgen.io.res.AirssTITL.spacegroup_label)


            * [`AirssTITL.volume`](pymatgen.io.md#pymatgen.io.res.AirssTITL.volume)


        * [`Ion`](pymatgen.io.md#pymatgen.io.res.Ion)


            * [`Ion.occupancy`](pymatgen.io.md#pymatgen.io.res.Ion.occupancy)


            * [`Ion.pos`](pymatgen.io.md#pymatgen.io.res.Ion.pos)


            * [`Ion.specie`](pymatgen.io.md#pymatgen.io.res.Ion.specie)


            * [`Ion.specie_num`](pymatgen.io.md#pymatgen.io.res.Ion.specie_num)


            * [`Ion.spin`](pymatgen.io.md#pymatgen.io.res.Ion.spin)


        * [`Res`](pymatgen.io.md#pymatgen.io.res.Res)


            * [`Res.CELL`](pymatgen.io.md#pymatgen.io.res.Res.CELL)


            * [`Res.REMS`](pymatgen.io.md#pymatgen.io.res.Res.REMS)


            * [`Res.SFAC`](pymatgen.io.md#pymatgen.io.res.Res.SFAC)


            * [`Res.TITL`](pymatgen.io.md#pymatgen.io.res.Res.TITL)


        * [`ResCELL`](pymatgen.io.md#pymatgen.io.res.ResCELL)


            * [`ResCELL.a`](pymatgen.io.md#pymatgen.io.res.ResCELL.a)


            * [`ResCELL.alpha`](pymatgen.io.md#pymatgen.io.res.ResCELL.alpha)


            * [`ResCELL.b`](pymatgen.io.md#pymatgen.io.res.ResCELL.b)


            * [`ResCELL.beta`](pymatgen.io.md#pymatgen.io.res.ResCELL.beta)


            * [`ResCELL.c`](pymatgen.io.md#pymatgen.io.res.ResCELL.c)


            * [`ResCELL.gamma`](pymatgen.io.md#pymatgen.io.res.ResCELL.gamma)


            * [`ResCELL.unknown_field_1`](pymatgen.io.md#pymatgen.io.res.ResCELL.unknown_field_1)


        * [`ResError`](pymatgen.io.md#pymatgen.io.res.ResError)


        * [`ResIO`](pymatgen.io.md#pymatgen.io.res.ResIO)


            * [`ResIO.entry_from_file()`](pymatgen.io.md#pymatgen.io.res.ResIO.entry_from_file)


            * [`ResIO.entry_from_str()`](pymatgen.io.md#pymatgen.io.res.ResIO.entry_from_str)


            * [`ResIO.entry_to_file()`](pymatgen.io.md#pymatgen.io.res.ResIO.entry_to_file)


            * [`ResIO.entry_to_str()`](pymatgen.io.md#pymatgen.io.res.ResIO.entry_to_str)


            * [`ResIO.structure_from_file()`](pymatgen.io.md#pymatgen.io.res.ResIO.structure_from_file)


            * [`ResIO.structure_from_str()`](pymatgen.io.md#pymatgen.io.res.ResIO.structure_from_str)


            * [`ResIO.structure_to_file()`](pymatgen.io.md#pymatgen.io.res.ResIO.structure_to_file)


            * [`ResIO.structure_to_str()`](pymatgen.io.md#pymatgen.io.res.ResIO.structure_to_str)


        * [`ResParseError`](pymatgen.io.md#pymatgen.io.res.ResParseError)


        * [`ResParser`](pymatgen.io.md#pymatgen.io.res.ResParser)


            * [`ResParser._parse_cell()`](pymatgen.io.md#pymatgen.io.res.ResParser._parse_cell)


            * [`ResParser._parse_file()`](pymatgen.io.md#pymatgen.io.res.ResParser._parse_file)


            * [`ResParser._parse_ion()`](pymatgen.io.md#pymatgen.io.res.ResParser._parse_ion)


            * [`ResParser._parse_sfac()`](pymatgen.io.md#pymatgen.io.res.ResParser._parse_sfac)


            * [`ResParser._parse_str()`](pymatgen.io.md#pymatgen.io.res.ResParser._parse_str)


            * [`ResParser._parse_titl()`](pymatgen.io.md#pymatgen.io.res.ResParser._parse_titl)


            * [`ResParser._parse_txt()`](pymatgen.io.md#pymatgen.io.res.ResParser._parse_txt)


        * [`ResProvider`](pymatgen.io.md#pymatgen.io.res.ResProvider)


            * [`ResProvider._site_spin()`](pymatgen.io.md#pymatgen.io.res.ResProvider._site_spin)


            * [`ResProvider.from_file()`](pymatgen.io.md#pymatgen.io.res.ResProvider.from_file)


            * [`ResProvider.from_str()`](pymatgen.io.md#pymatgen.io.res.ResProvider.from_str)


            * [`ResProvider.lattice`](pymatgen.io.md#pymatgen.io.res.ResProvider.lattice)


            * [`ResProvider.rems`](pymatgen.io.md#pymatgen.io.res.ResProvider.rems)


            * [`ResProvider.sites`](pymatgen.io.md#pymatgen.io.res.ResProvider.sites)


            * [`ResProvider.structure`](pymatgen.io.md#pymatgen.io.res.ResProvider.structure)


        * [`ResSFAC`](pymatgen.io.md#pymatgen.io.res.ResSFAC)


            * [`ResSFAC.ions`](pymatgen.io.md#pymatgen.io.res.ResSFAC.ions)


            * [`ResSFAC.species`](pymatgen.io.md#pymatgen.io.res.ResSFAC.species)


        * [`ResWriter`](pymatgen.io.md#pymatgen.io.res.ResWriter)


            * [`ResWriter._cell_from_lattice()`](pymatgen.io.md#pymatgen.io.res.ResWriter._cell_from_lattice)


            * [`ResWriter._ions_from_sites()`](pymatgen.io.md#pymatgen.io.res.ResWriter._ions_from_sites)


            * [`ResWriter._res_from_entry()`](pymatgen.io.md#pymatgen.io.res.ResWriter._res_from_entry)


            * [`ResWriter._res_from_structure()`](pymatgen.io.md#pymatgen.io.res.ResWriter._res_from_structure)


            * [`ResWriter._sfac_from_sites()`](pymatgen.io.md#pymatgen.io.res.ResWriter._sfac_from_sites)


            * [`ResWriter.string`](pymatgen.io.md#pymatgen.io.res.ResWriter.string)


            * [`ResWriter.write()`](pymatgen.io.md#pymatgen.io.res.ResWriter.write)


    * [pymatgen.io.shengbte module](pymatgen.io.md#module-pymatgen.io.shengbte)


        * [`Control`](pymatgen.io.md#pymatgen.io.shengbte.Control)


            * [`Control.allocations_keys`](pymatgen.io.md#pymatgen.io.shengbte.Control.allocations_keys)


            * [`Control.as_dict()`](pymatgen.io.md#pymatgen.io.shengbte.Control.as_dict)


            * [`Control.crystal_keys`](pymatgen.io.md#pymatgen.io.shengbte.Control.crystal_keys)


            * [`Control.data_keys`](pymatgen.io.md#pymatgen.io.shengbte.Control.data_keys)


            * [`Control.flags_keys`](pymatgen.io.md#pymatgen.io.shengbte.Control.flags_keys)


            * [`Control.from_dict()`](pymatgen.io.md#pymatgen.io.shengbte.Control.from_dict)


            * [`Control.from_file()`](pymatgen.io.md#pymatgen.io.shengbte.Control.from_file)


            * [`Control.from_structure()`](pymatgen.io.md#pymatgen.io.shengbte.Control.from_structure)


            * [`Control.get_structure()`](pymatgen.io.md#pymatgen.io.shengbte.Control.get_structure)


            * [`Control.params_keys`](pymatgen.io.md#pymatgen.io.shengbte.Control.params_keys)


            * [`Control.required_params`](pymatgen.io.md#pymatgen.io.shengbte.Control.required_params)


            * [`Control.to_file()`](pymatgen.io.md#pymatgen.io.shengbte.Control.to_file)


        * [`_get_subdict()`](pymatgen.io.md#pymatgen.io.shengbte._get_subdict)


    * [pymatgen.io.template module](pymatgen.io.md#module-pymatgen.io.template)


        * [`TemplateInputGen`](pymatgen.io.md#pymatgen.io.template.TemplateInputGen)


            * [`TemplateInputGen.get_input_set()`](pymatgen.io.md#pymatgen.io.template.TemplateInputGen.get_input_set)


    * [pymatgen.io.wannier90 module](pymatgen.io.md#module-pymatgen.io.wannier90)


        * [`Unk`](pymatgen.io.md#pymatgen.io.wannier90.Unk)


            * [`Unk.ik`](pymatgen.io.md#pymatgen.io.wannier90.Unk.ik)


            * [`Unk.data`](pymatgen.io.md#pymatgen.io.wannier90.Unk.data)


            * [`Unk.is_noncollinear`](pymatgen.io.md#pymatgen.io.wannier90.Unk.is_noncollinear)


            * [`Unk.nbnd`](pymatgen.io.md#pymatgen.io.wannier90.Unk.nbnd)


            * [`Unk.ng`](pymatgen.io.md#pymatgen.io.wannier90.Unk.ng)


            * [`Unk.data`](pymatgen.io.md#id3)


            * [`Unk.from_file()`](pymatgen.io.md#pymatgen.io.wannier90.Unk.from_file)


            * [`Unk.ik`](pymatgen.io.md#id4)


            * [`Unk.is_noncollinear`](pymatgen.io.md#id5)


            * [`Unk.nbnd`](pymatgen.io.md#id6)


            * [`Unk.ng`](pymatgen.io.md#id7)


            * [`Unk.write_file()`](pymatgen.io.md#pymatgen.io.wannier90.Unk.write_file)


    * [pymatgen.io.xcrysden module](pymatgen.io.md#module-pymatgen.io.xcrysden)


        * [`XSF`](pymatgen.io.md#pymatgen.io.xcrysden.XSF)


            * [`XSF.from_str()`](pymatgen.io.md#pymatgen.io.xcrysden.XSF.from_str)


            * [`XSF.from_string()`](pymatgen.io.md#pymatgen.io.xcrysden.XSF.from_string)


            * [`XSF.to_str()`](pymatgen.io.md#pymatgen.io.xcrysden.XSF.to_str)


            * [`XSF.to_string()`](pymatgen.io.md#pymatgen.io.xcrysden.XSF.to_string)


    * [pymatgen.io.xr module](pymatgen.io.md#module-pymatgen.io.xr)


        * [`Xr`](pymatgen.io.md#pymatgen.io.xr.Xr)


            * [`Xr.from_file()`](pymatgen.io.md#pymatgen.io.xr.Xr.from_file)


            * [`Xr.from_str()`](pymatgen.io.md#pymatgen.io.xr.Xr.from_str)


            * [`Xr.from_string()`](pymatgen.io.md#pymatgen.io.xr.Xr.from_string)


            * [`Xr.write_file()`](pymatgen.io.md#pymatgen.io.xr.Xr.write_file)


    * [pymatgen.io.xyz module](pymatgen.io.md#module-pymatgen.io.xyz)


        * [`XYZ`](pymatgen.io.md#pymatgen.io.xyz.XYZ)


            * [`XYZ._frame_str()`](pymatgen.io.md#pymatgen.io.xyz.XYZ._frame_str)


            * [`XYZ._from_frame_string()`](pymatgen.io.md#pymatgen.io.xyz.XYZ._from_frame_string)


            * [`XYZ.all_molecules`](pymatgen.io.md#pymatgen.io.xyz.XYZ.all_molecules)


            * [`XYZ.as_dataframe()`](pymatgen.io.md#pymatgen.io.xyz.XYZ.as_dataframe)


            * [`XYZ.from_file()`](pymatgen.io.md#pymatgen.io.xyz.XYZ.from_file)


            * [`XYZ.from_str()`](pymatgen.io.md#pymatgen.io.xyz.XYZ.from_str)


            * [`XYZ.from_string()`](pymatgen.io.md#pymatgen.io.xyz.XYZ.from_string)


            * [`XYZ.molecule`](pymatgen.io.md#pymatgen.io.xyz.XYZ.molecule)


            * [`XYZ.write_file()`](pymatgen.io.md#pymatgen.io.xyz.XYZ.write_file)


    * [pymatgen.io.zeopp module](pymatgen.io.md#module-pymatgen.io.zeopp)


        * [Zeo++ Installation Steps:](pymatgen.io.md#zeo-installation-steps)


        * [Zeo++ Post-Installation Checking:](pymatgen.io.md#zeo-post-installation-checking)


        * [`ZeoCssr`](pymatgen.io.md#pymatgen.io.zeopp.ZeoCssr)


            * [`ZeoCssr.from_file()`](pymatgen.io.md#pymatgen.io.zeopp.ZeoCssr.from_file)


            * [`ZeoCssr.from_str()`](pymatgen.io.md#pymatgen.io.zeopp.ZeoCssr.from_str)


            * [`ZeoCssr.from_string()`](pymatgen.io.md#pymatgen.io.zeopp.ZeoCssr.from_string)


        * [`ZeoVoronoiXYZ`](pymatgen.io.md#pymatgen.io.zeopp.ZeoVoronoiXYZ)


            * [`ZeoVoronoiXYZ.from_file()`](pymatgen.io.md#pymatgen.io.zeopp.ZeoVoronoiXYZ.from_file)


            * [`ZeoVoronoiXYZ.from_str()`](pymatgen.io.md#pymatgen.io.zeopp.ZeoVoronoiXYZ.from_str)


        * [`get_free_sphere_params()`](pymatgen.io.md#pymatgen.io.zeopp.get_free_sphere_params)


        * [`get_high_accuracy_voronoi_nodes()`](pymatgen.io.md#pymatgen.io.zeopp.get_high_accuracy_voronoi_nodes)


        * [`get_voronoi_nodes()`](pymatgen.io.md#pymatgen.io.zeopp.get_voronoi_nodes)


* [pymatgen.optimization package](pymatgen.optimization.md)




    * [pymatgen.optimization.linear_assignment module](pymatgen.optimization.md#module-pymatgen.optimization.linear_assignment)


        * [`LinearAssignment`](pymatgen.optimization.md#pymatgen.optimization.linear_assignment.LinearAssignment)


    * [pymatgen.optimization.neighbors module](pymatgen.optimization.md#module-pymatgen.optimization.neighbors)


        * [`find_points_in_spheres()`](pymatgen.optimization.md#pymatgen.optimization.neighbors.find_points_in_spheres)


* [pymatgen.phonon package](pymatgen.phonon.md)




    * [pymatgen.phonon.bandstructure module](pymatgen.phonon.md#module-pymatgen.phonon.bandstructure)


        * [`PhononBandStructure`](pymatgen.phonon.md#pymatgen.phonon.bandstructure.PhononBandStructure)


            * [`PhononBandStructure.as_dict()`](pymatgen.phonon.md#pymatgen.phonon.bandstructure.PhononBandStructure.as_dict)


            * [`PhononBandStructure.asr_breaking()`](pymatgen.phonon.md#pymatgen.phonon.bandstructure.PhononBandStructure.asr_breaking)


            * [`PhononBandStructure.from_dict()`](pymatgen.phonon.md#pymatgen.phonon.bandstructure.PhononBandStructure.from_dict)


            * [`PhononBandStructure.get_nac_eigendisplacements_along_dir()`](pymatgen.phonon.md#pymatgen.phonon.bandstructure.PhononBandStructure.get_nac_eigendisplacements_along_dir)


            * [`PhononBandStructure.get_nac_frequencies_along_dir()`](pymatgen.phonon.md#pymatgen.phonon.bandstructure.PhononBandStructure.get_nac_frequencies_along_dir)


            * [`PhononBandStructure.has_eigendisplacements`](pymatgen.phonon.md#pymatgen.phonon.bandstructure.PhononBandStructure.has_eigendisplacements)


            * [`PhononBandStructure.has_imaginary_freq()`](pymatgen.phonon.md#pymatgen.phonon.bandstructure.PhononBandStructure.has_imaginary_freq)


            * [`PhononBandStructure.has_nac`](pymatgen.phonon.md#pymatgen.phonon.bandstructure.PhononBandStructure.has_nac)


            * [`PhononBandStructure.min_freq()`](pymatgen.phonon.md#pymatgen.phonon.bandstructure.PhononBandStructure.min_freq)


        * [`PhononBandStructureSymmLine`](pymatgen.phonon.md#pymatgen.phonon.bandstructure.PhononBandStructureSymmLine)


            * [`PhononBandStructureSymmLine._reuse_init()`](pymatgen.phonon.md#pymatgen.phonon.bandstructure.PhononBandStructureSymmLine._reuse_init)


            * [`PhononBandStructureSymmLine.as_dict()`](pymatgen.phonon.md#pymatgen.phonon.bandstructure.PhononBandStructureSymmLine.as_dict)


            * [`PhononBandStructureSymmLine.as_phononwebsite()`](pymatgen.phonon.md#pymatgen.phonon.bandstructure.PhononBandStructureSymmLine.as_phononwebsite)


            * [`PhononBandStructureSymmLine.band_reorder()`](pymatgen.phonon.md#pymatgen.phonon.bandstructure.PhononBandStructureSymmLine.band_reorder)


            * [`PhononBandStructureSymmLine.from_dict()`](pymatgen.phonon.md#pymatgen.phonon.bandstructure.PhononBandStructureSymmLine.from_dict)


            * [`PhononBandStructureSymmLine.get_branch()`](pymatgen.phonon.md#pymatgen.phonon.bandstructure.PhononBandStructureSymmLine.get_branch)


            * [`PhononBandStructureSymmLine.get_equivalent_qpoints()`](pymatgen.phonon.md#pymatgen.phonon.bandstructure.PhononBandStructureSymmLine.get_equivalent_qpoints)


            * [`PhononBandStructureSymmLine.write_phononwebsite()`](pymatgen.phonon.md#pymatgen.phonon.bandstructure.PhononBandStructureSymmLine.write_phononwebsite)


        * [`eigenvectors_from_displacements()`](pymatgen.phonon.md#pymatgen.phonon.bandstructure.eigenvectors_from_displacements)


        * [`estimate_band_connection()`](pymatgen.phonon.md#pymatgen.phonon.bandstructure.estimate_band_connection)


        * [`get_reasonable_repetitions()`](pymatgen.phonon.md#pymatgen.phonon.bandstructure.get_reasonable_repetitions)


    * [pymatgen.phonon.dos module](pymatgen.phonon.md#module-pymatgen.phonon.dos)


        * [`CompletePhononDos`](pymatgen.phonon.md#pymatgen.phonon.dos.CompletePhononDos)


            * [`CompletePhononDos.pdos`](pymatgen.phonon.md#pymatgen.phonon.dos.CompletePhononDos.pdos)


            * [`CompletePhononDos.as_dict()`](pymatgen.phonon.md#pymatgen.phonon.dos.CompletePhononDos.as_dict)


            * [`CompletePhononDos.from_dict()`](pymatgen.phonon.md#pymatgen.phonon.dos.CompletePhononDos.from_dict)


            * [`CompletePhononDos.get_element_dos()`](pymatgen.phonon.md#pymatgen.phonon.dos.CompletePhononDos.get_element_dos)


            * [`CompletePhononDos.get_site_dos()`](pymatgen.phonon.md#pymatgen.phonon.dos.CompletePhononDos.get_site_dos)


        * [`PhononDos`](pymatgen.phonon.md#pymatgen.phonon.dos.PhononDos)


            * [`PhononDos._positive_densities()`](pymatgen.phonon.md#pymatgen.phonon.dos.PhononDos._positive_densities)


            * [`PhononDos._positive_frequencies()`](pymatgen.phonon.md#pymatgen.phonon.dos.PhononDos._positive_frequencies)


            * [`PhononDos.as_dict()`](pymatgen.phonon.md#pymatgen.phonon.dos.PhononDos.as_dict)


            * [`PhononDos.cv()`](pymatgen.phonon.md#pymatgen.phonon.dos.PhononDos.cv)


            * [`PhononDos.entropy()`](pymatgen.phonon.md#pymatgen.phonon.dos.PhononDos.entropy)


            * [`PhononDos.from_dict()`](pymatgen.phonon.md#pymatgen.phonon.dos.PhononDos.from_dict)


            * [`PhononDos.get_interpolated_value()`](pymatgen.phonon.md#pymatgen.phonon.dos.PhononDos.get_interpolated_value)


            * [`PhononDos.get_smeared_densities()`](pymatgen.phonon.md#pymatgen.phonon.dos.PhononDos.get_smeared_densities)


            * [`PhononDos.helmholtz_free_energy()`](pymatgen.phonon.md#pymatgen.phonon.dos.PhononDos.helmholtz_free_energy)


            * [`PhononDos.ind_zero_freq()`](pymatgen.phonon.md#pymatgen.phonon.dos.PhononDos.ind_zero_freq)


            * [`PhononDos.internal_energy()`](pymatgen.phonon.md#pymatgen.phonon.dos.PhononDos.internal_energy)


            * [`PhononDos.zero_point_energy()`](pymatgen.phonon.md#pymatgen.phonon.dos.PhononDos.zero_point_energy)


        * [`coth()`](pymatgen.phonon.md#pymatgen.phonon.dos.coth)


    * [pymatgen.phonon.gruneisen module](pymatgen.phonon.md#module-pymatgen.phonon.gruneisen)


        * [`GruneisenParameter`](pymatgen.phonon.md#pymatgen.phonon.gruneisen.GruneisenParameter)


            * [`GruneisenParameter.acoustic_debye_temp`](pymatgen.phonon.md#pymatgen.phonon.gruneisen.GruneisenParameter.acoustic_debye_temp)


            * [`GruneisenParameter.average_gruneisen()`](pymatgen.phonon.md#pymatgen.phonon.gruneisen.GruneisenParameter.average_gruneisen)


            * [`GruneisenParameter.debye_temp_limit`](pymatgen.phonon.md#pymatgen.phonon.gruneisen.GruneisenParameter.debye_temp_limit)


            * [`GruneisenParameter.debye_temp_phonopy()`](pymatgen.phonon.md#pymatgen.phonon.gruneisen.GruneisenParameter.debye_temp_phonopy)


            * [`GruneisenParameter.phdos`](pymatgen.phonon.md#pymatgen.phonon.gruneisen.GruneisenParameter.phdos)


            * [`GruneisenParameter.tdos`](pymatgen.phonon.md#pymatgen.phonon.gruneisen.GruneisenParameter.tdos)


            * [`GruneisenParameter.thermal_conductivity_slack()`](pymatgen.phonon.md#pymatgen.phonon.gruneisen.GruneisenParameter.thermal_conductivity_slack)


        * [`GruneisenPhononBandStructure`](pymatgen.phonon.md#pymatgen.phonon.gruneisen.GruneisenPhononBandStructure)


            * [`GruneisenPhononBandStructure.as_dict()`](pymatgen.phonon.md#pymatgen.phonon.gruneisen.GruneisenPhononBandStructure.as_dict)


            * [`GruneisenPhononBandStructure.from_dict()`](pymatgen.phonon.md#pymatgen.phonon.gruneisen.GruneisenPhononBandStructure.from_dict)


        * [`GruneisenPhononBandStructureSymmLine`](pymatgen.phonon.md#pymatgen.phonon.gruneisen.GruneisenPhononBandStructureSymmLine)


            * [`GruneisenPhononBandStructureSymmLine.from_dict()`](pymatgen.phonon.md#pymatgen.phonon.gruneisen.GruneisenPhononBandStructureSymmLine.from_dict)


    * [pymatgen.phonon.ir_spectra module](pymatgen.phonon.md#module-pymatgen.phonon.ir_spectra)


        * [`IRDielectricTensor`](pymatgen.phonon.md#pymatgen.phonon.ir_spectra.IRDielectricTensor)


            * [`IRDielectricTensor.as_dict()`](pymatgen.phonon.md#pymatgen.phonon.ir_spectra.IRDielectricTensor.as_dict)


            * [`IRDielectricTensor.from_dict()`](pymatgen.phonon.md#pymatgen.phonon.ir_spectra.IRDielectricTensor.from_dict)


            * [`IRDielectricTensor.get_ir_spectra()`](pymatgen.phonon.md#pymatgen.phonon.ir_spectra.IRDielectricTensor.get_ir_spectra)


            * [`IRDielectricTensor.get_plotter()`](pymatgen.phonon.md#pymatgen.phonon.ir_spectra.IRDielectricTensor.get_plotter)


            * [`IRDielectricTensor.get_spectrum()`](pymatgen.phonon.md#pymatgen.phonon.ir_spectra.IRDielectricTensor.get_spectrum)


            * [`IRDielectricTensor.max_phfreq`](pymatgen.phonon.md#pymatgen.phonon.ir_spectra.IRDielectricTensor.max_phfreq)


            * [`IRDielectricTensor.nph_freqs`](pymatgen.phonon.md#pymatgen.phonon.ir_spectra.IRDielectricTensor.nph_freqs)


            * [`IRDielectricTensor.plot()`](pymatgen.phonon.md#pymatgen.phonon.ir_spectra.IRDielectricTensor.plot)


            * [`IRDielectricTensor.write_json()`](pymatgen.phonon.md#pymatgen.phonon.ir_spectra.IRDielectricTensor.write_json)


    * [pymatgen.phonon.plotter module](pymatgen.phonon.md#module-pymatgen.phonon.plotter)


        * [`FreqUnits`](pymatgen.phonon.md#pymatgen.phonon.plotter.FreqUnits)


            * [`FreqUnits._asdict()`](pymatgen.phonon.md#pymatgen.phonon.plotter.FreqUnits._asdict)


            * [`FreqUnits._field_defaults`](pymatgen.phonon.md#pymatgen.phonon.plotter.FreqUnits._field_defaults)


            * [`FreqUnits._fields`](pymatgen.phonon.md#pymatgen.phonon.plotter.FreqUnits._fields)


            * [`FreqUnits._make()`](pymatgen.phonon.md#pymatgen.phonon.plotter.FreqUnits._make)


            * [`FreqUnits._replace()`](pymatgen.phonon.md#pymatgen.phonon.plotter.FreqUnits._replace)


            * [`FreqUnits.factor`](pymatgen.phonon.md#pymatgen.phonon.plotter.FreqUnits.factor)


            * [`FreqUnits.label`](pymatgen.phonon.md#pymatgen.phonon.plotter.FreqUnits.label)


        * [`GruneisenPhononBSPlotter`](pymatgen.phonon.md#pymatgen.phonon.plotter.GruneisenPhononBSPlotter)


            * [`GruneisenPhononBSPlotter.bs_plot_data()`](pymatgen.phonon.md#pymatgen.phonon.plotter.GruneisenPhononBSPlotter.bs_plot_data)


            * [`GruneisenPhononBSPlotter.get_plot_gs()`](pymatgen.phonon.md#pymatgen.phonon.plotter.GruneisenPhononBSPlotter.get_plot_gs)


            * [`GruneisenPhononBSPlotter.plot_compare_gs()`](pymatgen.phonon.md#pymatgen.phonon.plotter.GruneisenPhononBSPlotter.plot_compare_gs)


            * [`GruneisenPhononBSPlotter.save_plot_gs()`](pymatgen.phonon.md#pymatgen.phonon.plotter.GruneisenPhononBSPlotter.save_plot_gs)


            * [`GruneisenPhononBSPlotter.show_gs()`](pymatgen.phonon.md#pymatgen.phonon.plotter.GruneisenPhononBSPlotter.show_gs)


        * [`GruneisenPlotter`](pymatgen.phonon.md#pymatgen.phonon.plotter.GruneisenPlotter)


            * [`GruneisenPlotter.get_plot()`](pymatgen.phonon.md#pymatgen.phonon.plotter.GruneisenPlotter.get_plot)


            * [`GruneisenPlotter.save_plot()`](pymatgen.phonon.md#pymatgen.phonon.plotter.GruneisenPlotter.save_plot)


            * [`GruneisenPlotter.show()`](pymatgen.phonon.md#pymatgen.phonon.plotter.GruneisenPlotter.show)


        * [`PhononBSPlotter`](pymatgen.phonon.md#pymatgen.phonon.plotter.PhononBSPlotter)


            * [`PhononBSPlotter._get_weight()`](pymatgen.phonon.md#pymatgen.phonon.plotter.PhononBSPlotter._get_weight)


            * [`PhononBSPlotter._make_color()`](pymatgen.phonon.md#pymatgen.phonon.plotter.PhononBSPlotter._make_color)


            * [`PhononBSPlotter._make_ticks()`](pymatgen.phonon.md#pymatgen.phonon.plotter.PhononBSPlotter._make_ticks)


            * [`PhononBSPlotter.bs_plot_data()`](pymatgen.phonon.md#pymatgen.phonon.plotter.PhononBSPlotter.bs_plot_data)


            * [`PhononBSPlotter.get_plot()`](pymatgen.phonon.md#pymatgen.phonon.plotter.PhononBSPlotter.get_plot)


            * [`PhononBSPlotter.get_proj_plot()`](pymatgen.phonon.md#pymatgen.phonon.plotter.PhononBSPlotter.get_proj_plot)


            * [`PhononBSPlotter.get_ticks()`](pymatgen.phonon.md#pymatgen.phonon.plotter.PhononBSPlotter.get_ticks)


            * [`PhononBSPlotter.plot_brillouin()`](pymatgen.phonon.md#pymatgen.phonon.plotter.PhononBSPlotter.plot_brillouin)


            * [`PhononBSPlotter.plot_compare()`](pymatgen.phonon.md#pymatgen.phonon.plotter.PhononBSPlotter.plot_compare)


            * [`PhononBSPlotter.save_plot()`](pymatgen.phonon.md#pymatgen.phonon.plotter.PhononBSPlotter.save_plot)


            * [`PhononBSPlotter.show()`](pymatgen.phonon.md#pymatgen.phonon.plotter.PhononBSPlotter.show)


            * [`PhononBSPlotter.show_proj()`](pymatgen.phonon.md#pymatgen.phonon.plotter.PhononBSPlotter.show_proj)


        * [`PhononDosPlotter`](pymatgen.phonon.md#pymatgen.phonon.plotter.PhononDosPlotter)


            * [`PhononDosPlotter.add_dos()`](pymatgen.phonon.md#pymatgen.phonon.plotter.PhononDosPlotter.add_dos)


            * [`PhononDosPlotter.add_dos_dict()`](pymatgen.phonon.md#pymatgen.phonon.plotter.PhononDosPlotter.add_dos_dict)


            * [`PhononDosPlotter.get_dos_dict()`](pymatgen.phonon.md#pymatgen.phonon.plotter.PhononDosPlotter.get_dos_dict)


            * [`PhononDosPlotter.get_plot()`](pymatgen.phonon.md#pymatgen.phonon.plotter.PhononDosPlotter.get_plot)


            * [`PhononDosPlotter.save_plot()`](pymatgen.phonon.md#pymatgen.phonon.plotter.PhononDosPlotter.save_plot)


            * [`PhononDosPlotter.show()`](pymatgen.phonon.md#pymatgen.phonon.plotter.PhononDosPlotter.show)


        * [`ThermoPlotter`](pymatgen.phonon.md#pymatgen.phonon.plotter.ThermoPlotter)


            * [`ThermoPlotter._plot_thermo()`](pymatgen.phonon.md#pymatgen.phonon.plotter.ThermoPlotter._plot_thermo)


            * [`ThermoPlotter.plot_cv()`](pymatgen.phonon.md#pymatgen.phonon.plotter.ThermoPlotter.plot_cv)


            * [`ThermoPlotter.plot_entropy()`](pymatgen.phonon.md#pymatgen.phonon.plotter.ThermoPlotter.plot_entropy)


            * [`ThermoPlotter.plot_helmholtz_free_energy()`](pymatgen.phonon.md#pymatgen.phonon.plotter.ThermoPlotter.plot_helmholtz_free_energy)


            * [`ThermoPlotter.plot_internal_energy()`](pymatgen.phonon.md#pymatgen.phonon.plotter.ThermoPlotter.plot_internal_energy)


            * [`ThermoPlotter.plot_thermodynamic_properties()`](pymatgen.phonon.md#pymatgen.phonon.plotter.ThermoPlotter.plot_thermodynamic_properties)


        * [`freq_units()`](pymatgen.phonon.md#pymatgen.phonon.plotter.freq_units)


    * [pymatgen.phonon.thermal_displacements module](pymatgen.phonon.md#module-pymatgen.phonon.thermal_displacements)


        * [`ThermalDisplacementMatrices`](pymatgen.phonon.md#pymatgen.phonon.thermal_displacements.ThermalDisplacementMatrices)


            * [`ThermalDisplacementMatrices.B`](pymatgen.phonon.md#pymatgen.phonon.thermal_displacements.ThermalDisplacementMatrices.B)


            * [`ThermalDisplacementMatrices.U1U2U3`](pymatgen.phonon.md#pymatgen.phonon.thermal_displacements.ThermalDisplacementMatrices.U1U2U3)


            * [`ThermalDisplacementMatrices.Ucif`](pymatgen.phonon.md#pymatgen.phonon.thermal_displacements.ThermalDisplacementMatrices.Ucif)


            * [`ThermalDisplacementMatrices.Ustar`](pymatgen.phonon.md#pymatgen.phonon.thermal_displacements.ThermalDisplacementMatrices.Ustar)


            * [`ThermalDisplacementMatrices._angle_dot()`](pymatgen.phonon.md#pymatgen.phonon.thermal_displacements.ThermalDisplacementMatrices._angle_dot)


            * [`ThermalDisplacementMatrices.beta`](pymatgen.phonon.md#pymatgen.phonon.thermal_displacements.ThermalDisplacementMatrices.beta)


            * [`ThermalDisplacementMatrices.compute_directionality_quality_criterion()`](pymatgen.phonon.md#pymatgen.phonon.thermal_displacements.ThermalDisplacementMatrices.compute_directionality_quality_criterion)


            * [`ThermalDisplacementMatrices.from_Ucif()`](pymatgen.phonon.md#pymatgen.phonon.thermal_displacements.ThermalDisplacementMatrices.from_Ucif)


            * [`ThermalDisplacementMatrices.from_cif_P1()`](pymatgen.phonon.md#pymatgen.phonon.thermal_displacements.ThermalDisplacementMatrices.from_cif_P1)


            * [`ThermalDisplacementMatrices.from_structure_with_site_properties_Ucif()`](pymatgen.phonon.md#pymatgen.phonon.thermal_displacements.ThermalDisplacementMatrices.from_structure_with_site_properties_Ucif)


            * [`ThermalDisplacementMatrices.get_full_matrix()`](pymatgen.phonon.md#pymatgen.phonon.thermal_displacements.ThermalDisplacementMatrices.get_full_matrix)


            * [`ThermalDisplacementMatrices.get_reduced_matrix()`](pymatgen.phonon.md#pymatgen.phonon.thermal_displacements.ThermalDisplacementMatrices.get_reduced_matrix)


            * [`ThermalDisplacementMatrices.ratio_prolate`](pymatgen.phonon.md#pymatgen.phonon.thermal_displacements.ThermalDisplacementMatrices.ratio_prolate)


            * [`ThermalDisplacementMatrices.to_structure_with_site_properties_Ucif()`](pymatgen.phonon.md#pymatgen.phonon.thermal_displacements.ThermalDisplacementMatrices.to_structure_with_site_properties_Ucif)


            * [`ThermalDisplacementMatrices.visualize_directionality_quality_criterion()`](pymatgen.phonon.md#pymatgen.phonon.thermal_displacements.ThermalDisplacementMatrices.visualize_directionality_quality_criterion)


            * [`ThermalDisplacementMatrices.write_cif()`](pymatgen.phonon.md#pymatgen.phonon.thermal_displacements.ThermalDisplacementMatrices.write_cif)


* [pymatgen.symmetry package](pymatgen.symmetry.md)




    * [pymatgen.symmetry.analyzer module](pymatgen.symmetry.md#module-pymatgen.symmetry.analyzer)


        * [`PointGroupAnalyzer`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.PointGroupAnalyzer)


            * [`PointGroupAnalyzer._analyze()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.PointGroupAnalyzer._analyze)


            * [`PointGroupAnalyzer._check_R2_axes_asym()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.PointGroupAnalyzer._check_R2_axes_asym)


            * [`PointGroupAnalyzer._check_perpendicular_r2_axis()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.PointGroupAnalyzer._check_perpendicular_r2_axis)


            * [`PointGroupAnalyzer._check_rot_sym()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.PointGroupAnalyzer._check_rot_sym)


            * [`PointGroupAnalyzer._combine_eq_sets()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.PointGroupAnalyzer._combine_eq_sets)


            * [`PointGroupAnalyzer._find_mirror()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.PointGroupAnalyzer._find_mirror)


            * [`PointGroupAnalyzer._find_spherical_axes()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.PointGroupAnalyzer._find_spherical_axes)


            * [`PointGroupAnalyzer._get_eq_sets()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.PointGroupAnalyzer._get_eq_sets)


            * [`PointGroupAnalyzer._get_smallest_set_not_on_axis()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.PointGroupAnalyzer._get_smallest_set_not_on_axis)


            * [`PointGroupAnalyzer._proc_asym_top()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.PointGroupAnalyzer._proc_asym_top)


            * [`PointGroupAnalyzer._proc_cyclic()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.PointGroupAnalyzer._proc_cyclic)


            * [`PointGroupAnalyzer._proc_dihedral()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.PointGroupAnalyzer._proc_dihedral)


            * [`PointGroupAnalyzer._proc_linear()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.PointGroupAnalyzer._proc_linear)


            * [`PointGroupAnalyzer._proc_no_rot_sym()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.PointGroupAnalyzer._proc_no_rot_sym)


            * [`PointGroupAnalyzer._proc_sph_top()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.PointGroupAnalyzer._proc_sph_top)


            * [`PointGroupAnalyzer._proc_sym_top()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.PointGroupAnalyzer._proc_sym_top)


            * [`PointGroupAnalyzer.get_equivalent_atoms()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.PointGroupAnalyzer.get_equivalent_atoms)


            * [`PointGroupAnalyzer.get_pointgroup()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.PointGroupAnalyzer.get_pointgroup)


            * [`PointGroupAnalyzer.get_rotational_symmetry_number()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.PointGroupAnalyzer.get_rotational_symmetry_number)


            * [`PointGroupAnalyzer.get_symmetry_operations()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.PointGroupAnalyzer.get_symmetry_operations)


            * [`PointGroupAnalyzer.inversion_op`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.PointGroupAnalyzer.inversion_op)


            * [`PointGroupAnalyzer.is_valid_op()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.PointGroupAnalyzer.is_valid_op)


            * [`PointGroupAnalyzer.symmetrize_molecule()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.PointGroupAnalyzer.symmetrize_molecule)


        * [`PointGroupOperations`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.PointGroupOperations)


            * [`PointGroupOperations.sch_symbol`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.PointGroupOperations.sch_symbol)


        * [`SpacegroupAnalyzer`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.SpacegroupAnalyzer)


            * [`SpacegroupAnalyzer._get_symmetry()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.SpacegroupAnalyzer._get_symmetry)


            * [`SpacegroupAnalyzer.find_primitive()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.SpacegroupAnalyzer.find_primitive)


            * [`SpacegroupAnalyzer.get_conventional_standard_structure()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.SpacegroupAnalyzer.get_conventional_standard_structure)


            * [`SpacegroupAnalyzer.get_conventional_to_primitive_transformation_matrix()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.SpacegroupAnalyzer.get_conventional_to_primitive_transformation_matrix)


            * [`SpacegroupAnalyzer.get_crystal_system()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.SpacegroupAnalyzer.get_crystal_system)


            * [`SpacegroupAnalyzer.get_hall()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.SpacegroupAnalyzer.get_hall)


            * [`SpacegroupAnalyzer.get_ir_reciprocal_mesh()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.SpacegroupAnalyzer.get_ir_reciprocal_mesh)


            * [`SpacegroupAnalyzer.get_ir_reciprocal_mesh_map()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.SpacegroupAnalyzer.get_ir_reciprocal_mesh_map)


            * [`SpacegroupAnalyzer.get_kpoint_weights()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.SpacegroupAnalyzer.get_kpoint_weights)


            * [`SpacegroupAnalyzer.get_lattice_type()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.SpacegroupAnalyzer.get_lattice_type)


            * [`SpacegroupAnalyzer.get_point_group_operations()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.SpacegroupAnalyzer.get_point_group_operations)


            * [`SpacegroupAnalyzer.get_point_group_symbol()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.SpacegroupAnalyzer.get_point_group_symbol)


            * [`SpacegroupAnalyzer.get_primitive_standard_structure()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.SpacegroupAnalyzer.get_primitive_standard_structure)


            * [`SpacegroupAnalyzer.get_refined_structure()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.SpacegroupAnalyzer.get_refined_structure)


            * [`SpacegroupAnalyzer.get_space_group_number()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.SpacegroupAnalyzer.get_space_group_number)


            * [`SpacegroupAnalyzer.get_space_group_operations()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.SpacegroupAnalyzer.get_space_group_operations)


            * [`SpacegroupAnalyzer.get_space_group_symbol()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.SpacegroupAnalyzer.get_space_group_symbol)


            * [`SpacegroupAnalyzer.get_symmetrized_structure()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.SpacegroupAnalyzer.get_symmetrized_structure)


            * [`SpacegroupAnalyzer.get_symmetry_dataset()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.SpacegroupAnalyzer.get_symmetry_dataset)


            * [`SpacegroupAnalyzer.get_symmetry_operations()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.SpacegroupAnalyzer.get_symmetry_operations)


            * [`SpacegroupAnalyzer.is_laue()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.SpacegroupAnalyzer.is_laue)


        * [`SpacegroupOperations`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.SpacegroupOperations)


            * [`SpacegroupOperations.are_symmetrically_equivalent()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.SpacegroupOperations.are_symmetrically_equivalent)


        * [`_get_symmetry_dataset()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer._get_symmetry_dataset)


        * [`cluster_sites()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.cluster_sites)


        * [`generate_full_symmops()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.generate_full_symmops)


        * [`iterative_symmetrize()`](pymatgen.symmetry.md#pymatgen.symmetry.analyzer.iterative_symmetrize)


    * [pymatgen.symmetry.bandstructure module](pymatgen.symmetry.md#module-pymatgen.symmetry.bandstructure)


        * [`HighSymmKpath`](pymatgen.symmetry.md#pymatgen.symmetry.bandstructure.HighSymmKpath)


            * [`HighSymmKpath._abc_impl`](pymatgen.symmetry.md#pymatgen.symmetry.bandstructure.HighSymmKpath._abc_impl)


            * [`HighSymmKpath._get_hin_kpath()`](pymatgen.symmetry.md#pymatgen.symmetry.bandstructure.HighSymmKpath._get_hin_kpath)


            * [`HighSymmKpath._get_klabels()`](pymatgen.symmetry.md#pymatgen.symmetry.bandstructure.HighSymmKpath._get_klabels)


            * [`HighSymmKpath._get_lm_kpath()`](pymatgen.symmetry.md#pymatgen.symmetry.bandstructure.HighSymmKpath._get_lm_kpath)


            * [`HighSymmKpath._get_sc_kpath()`](pymatgen.symmetry.md#pymatgen.symmetry.bandstructure.HighSymmKpath._get_sc_kpath)


            * [`HighSymmKpath.equiv_labels`](pymatgen.symmetry.md#pymatgen.symmetry.bandstructure.HighSymmKpath.equiv_labels)


            * [`HighSymmKpath.get_continuous_path()`](pymatgen.symmetry.md#pymatgen.symmetry.bandstructure.HighSymmKpath.get_continuous_path)


            * [`HighSymmKpath.label_index`](pymatgen.symmetry.md#pymatgen.symmetry.bandstructure.HighSymmKpath.label_index)


            * [`HighSymmKpath.path_lengths`](pymatgen.symmetry.md#pymatgen.symmetry.bandstructure.HighSymmKpath.path_lengths)


            * [`HighSymmKpath.path_type`](pymatgen.symmetry.md#pymatgen.symmetry.bandstructure.HighSymmKpath.path_type)


    * [pymatgen.symmetry.groups module](pymatgen.symmetry.md#module-pymatgen.symmetry.groups)


        * [`PointGroup`](pymatgen.symmetry.md#pymatgen.symmetry.groups.PointGroup)


            * [`PointGroup.symbol`](pymatgen.symmetry.md#pymatgen.symmetry.groups.PointGroup.symbol)


            * [`PointGroup.generators`](pymatgen.symmetry.md#pymatgen.symmetry.groups.PointGroup.generators)


            * [`PointGroup.symmetry_ops`](pymatgen.symmetry.md#pymatgen.symmetry.groups.PointGroup.symmetry_ops)


            * [`PointGroup._abc_impl`](pymatgen.symmetry.md#pymatgen.symmetry.groups.PointGroup._abc_impl)


        * [`SpaceGroup`](pymatgen.symmetry.md#pymatgen.symmetry.groups.SpaceGroup)


            * [`SpaceGroup.symbol`](pymatgen.symmetry.md#pymatgen.symmetry.groups.SpaceGroup.symbol)


            * [`SpaceGroup.int_number`](pymatgen.symmetry.md#pymatgen.symmetry.groups.SpaceGroup.int_number)


            * [`SpaceGroup.generators`](pymatgen.symmetry.md#pymatgen.symmetry.groups.SpaceGroup.generators)


            * [`SpaceGroup.order`](pymatgen.symmetry.md#pymatgen.symmetry.groups.SpaceGroup.order)


            * [`SpaceGroup._abc_impl`](pymatgen.symmetry.md#pymatgen.symmetry.groups.SpaceGroup._abc_impl)


        * [`SymmetryGroup`](pymatgen.symmetry.md#pymatgen.symmetry.groups.SymmetryGroup)


            * [`SymmetryGroup._abc_impl`](pymatgen.symmetry.md#pymatgen.symmetry.groups.SymmetryGroup._abc_impl)


            * [`SymmetryGroup.is_subgroup()`](pymatgen.symmetry.md#pymatgen.symmetry.groups.SymmetryGroup.is_subgroup)


            * [`SymmetryGroup.is_supergroup()`](pymatgen.symmetry.md#pymatgen.symmetry.groups.SymmetryGroup.is_supergroup)


            * [`SymmetryGroup.symmetry_ops`](pymatgen.symmetry.md#pymatgen.symmetry.groups.SymmetryGroup.symmetry_ops)


            * [`SymmetryGroup.to_latex_string()`](pymatgen.symmetry.md#pymatgen.symmetry.groups.SymmetryGroup.to_latex_string)


        * [`in_array_list()`](pymatgen.symmetry.md#pymatgen.symmetry.groups.in_array_list)


        * [`sg_symbol_from_int_number()`](pymatgen.symmetry.md#pymatgen.symmetry.groups.sg_symbol_from_int_number)


    * [pymatgen.symmetry.kpath module](pymatgen.symmetry.md#module-pymatgen.symmetry.kpath)


        * [`KPathBase`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathBase)


            * [`KPathBase._abc_impl`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathBase._abc_impl)


            * [`KPathBase.get_kpoints()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathBase.get_kpoints)


            * [`KPathBase.kpath`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathBase.kpath)


            * [`KPathBase.lattice`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathBase.lattice)


            * [`KPathBase.rec_lattice`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathBase.rec_lattice)


            * [`KPathBase.structure`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathBase.structure)


        * [`KPathLatimerMunro`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathLatimerMunro)


            * [`KPathLatimerMunro.LabelPoints()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathLatimerMunro.LabelPoints)


            * [`KPathLatimerMunro.LabelSymbol()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathLatimerMunro.LabelSymbol)


            * [`KPathLatimerMunro._abc_impl`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathLatimerMunro._abc_impl)


            * [`KPathLatimerMunro._all_ints()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathLatimerMunro._all_ints)


            * [`KPathLatimerMunro._apply_op_to_magmom()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathLatimerMunro._apply_op_to_magmom)


            * [`KPathLatimerMunro._choose_path()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathLatimerMunro._choose_path)


            * [`KPathLatimerMunro._closewrapped()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathLatimerMunro._closewrapped)


            * [`KPathLatimerMunro._convert_all_magmoms_to_vectors()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathLatimerMunro._convert_all_magmoms_to_vectors)


            * [`KPathLatimerMunro._get_IRBZ()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathLatimerMunro._get_IRBZ)


            * [`KPathLatimerMunro._get_coset_factor()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathLatimerMunro._get_coset_factor)


            * [`KPathLatimerMunro._get_key_line_orbits()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathLatimerMunro._get_key_line_orbits)


            * [`KPathLatimerMunro._get_key_lines()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathLatimerMunro._get_key_lines)


            * [`KPathLatimerMunro._get_key_point_orbits()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathLatimerMunro._get_key_point_orbits)


            * [`KPathLatimerMunro._get_key_points()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathLatimerMunro._get_key_points)


            * [`KPathLatimerMunro._get_ksymm_kpath()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathLatimerMunro._get_ksymm_kpath)


            * [`KPathLatimerMunro._get_little_groups()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathLatimerMunro._get_little_groups)


            * [`KPathLatimerMunro._get_magnetic_symmetry_operations()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathLatimerMunro._get_magnetic_symmetry_operations)


            * [`KPathLatimerMunro._get_max_cosine_labels()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathLatimerMunro._get_max_cosine_labels)


            * [`KPathLatimerMunro._get_orbit_labels()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathLatimerMunro._get_orbit_labels)


            * [`KPathLatimerMunro._get_reciprocal_point_group()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathLatimerMunro._get_reciprocal_point_group)


            * [`KPathLatimerMunro._get_reciprocal_point_group_dict()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathLatimerMunro._get_reciprocal_point_group_dict)


            * [`KPathLatimerMunro._kpath`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathLatimerMunro._kpath)


            * [`KPathLatimerMunro._op_maps_IRBZ_to_self()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathLatimerMunro._op_maps_IRBZ_to_self)


            * [`KPathLatimerMunro._reduce_IRBZ()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathLatimerMunro._reduce_IRBZ)


            * [`KPathLatimerMunro._reduce_cosines_array()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathLatimerMunro._reduce_cosines_array)


            * [`KPathLatimerMunro.mag_type`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathLatimerMunro.mag_type)


        * [`KPathSeek`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSeek)


            * [`KPathSeek._abc_impl`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSeek._abc_impl)


            * [`KPathSeek._kpath`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSeek._kpath)


            * [`KPathSeek._trans_sc_to_Hin()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSeek._trans_sc_to_Hin)


        * [`KPathSetyawanCurtarolo`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSetyawanCurtarolo)


            * [`KPathSetyawanCurtarolo._abc_impl`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSetyawanCurtarolo._abc_impl)


            * [`KPathSetyawanCurtarolo._kpath`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSetyawanCurtarolo._kpath)


            * [`KPathSetyawanCurtarolo.bcc()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSetyawanCurtarolo.bcc)


            * [`KPathSetyawanCurtarolo.bctet1()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSetyawanCurtarolo.bctet1)


            * [`KPathSetyawanCurtarolo.bctet2()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSetyawanCurtarolo.bctet2)


            * [`KPathSetyawanCurtarolo.conventional`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSetyawanCurtarolo.conventional)


            * [`KPathSetyawanCurtarolo.cubic()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSetyawanCurtarolo.cubic)


            * [`KPathSetyawanCurtarolo.fcc()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSetyawanCurtarolo.fcc)


            * [`KPathSetyawanCurtarolo.hex()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSetyawanCurtarolo.hex)


            * [`KPathSetyawanCurtarolo.mcl()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSetyawanCurtarolo.mcl)


            * [`KPathSetyawanCurtarolo.mclc1()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSetyawanCurtarolo.mclc1)


            * [`KPathSetyawanCurtarolo.mclc2()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSetyawanCurtarolo.mclc2)


            * [`KPathSetyawanCurtarolo.mclc3()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSetyawanCurtarolo.mclc3)


            * [`KPathSetyawanCurtarolo.mclc4()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSetyawanCurtarolo.mclc4)


            * [`KPathSetyawanCurtarolo.mclc5()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSetyawanCurtarolo.mclc5)


            * [`KPathSetyawanCurtarolo.orc()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSetyawanCurtarolo.orc)


            * [`KPathSetyawanCurtarolo.orcc()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSetyawanCurtarolo.orcc)


            * [`KPathSetyawanCurtarolo.orcf1()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSetyawanCurtarolo.orcf1)


            * [`KPathSetyawanCurtarolo.orcf2()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSetyawanCurtarolo.orcf2)


            * [`KPathSetyawanCurtarolo.orcf3()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSetyawanCurtarolo.orcf3)


            * [`KPathSetyawanCurtarolo.orci()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSetyawanCurtarolo.orci)


            * [`KPathSetyawanCurtarolo.prim`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSetyawanCurtarolo.prim)


            * [`KPathSetyawanCurtarolo.prim_rec`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSetyawanCurtarolo.prim_rec)


            * [`KPathSetyawanCurtarolo.rhl1()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSetyawanCurtarolo.rhl1)


            * [`KPathSetyawanCurtarolo.rhl2()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSetyawanCurtarolo.rhl2)


            * [`KPathSetyawanCurtarolo.tet()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSetyawanCurtarolo.tet)


            * [`KPathSetyawanCurtarolo.tria()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSetyawanCurtarolo.tria)


            * [`KPathSetyawanCurtarolo.trib()`](pymatgen.symmetry.md#pymatgen.symmetry.kpath.KPathSetyawanCurtarolo.trib)


    * [pymatgen.symmetry.maggroups module](pymatgen.symmetry.md#module-pymatgen.symmetry.maggroups)


        * [`MagneticSpaceGroup`](pymatgen.symmetry.md#pymatgen.symmetry.maggroups.MagneticSpaceGroup)


            * [`MagneticSpaceGroup._abc_impl`](pymatgen.symmetry.md#pymatgen.symmetry.maggroups.MagneticSpaceGroup._abc_impl)


        * [`_write_all_magnetic_space_groups_to_file()`](pymatgen.symmetry.md#pymatgen.symmetry.maggroups._write_all_magnetic_space_groups_to_file)


    * [pymatgen.symmetry.settings module](pymatgen.symmetry.md#module-pymatgen.symmetry.settings)


        * [`JonesFaithfulTransformation`](pymatgen.symmetry.md#pymatgen.symmetry.settings.JonesFaithfulTransformation)


            * [`JonesFaithfulTransformation.P`](pymatgen.symmetry.md#pymatgen.symmetry.settings.JonesFaithfulTransformation.P)


            * [`JonesFaithfulTransformation._get_transformation_string_from_Pp()`](pymatgen.symmetry.md#pymatgen.symmetry.settings.JonesFaithfulTransformation._get_transformation_string_from_Pp)


            * [`JonesFaithfulTransformation.from_origin_shift()`](pymatgen.symmetry.md#pymatgen.symmetry.settings.JonesFaithfulTransformation.from_origin_shift)


            * [`JonesFaithfulTransformation.from_transformation_str()`](pymatgen.symmetry.md#pymatgen.symmetry.settings.JonesFaithfulTransformation.from_transformation_str)


            * [`JonesFaithfulTransformation.from_transformation_string()`](pymatgen.symmetry.md#pymatgen.symmetry.settings.JonesFaithfulTransformation.from_transformation_string)


            * [`JonesFaithfulTransformation.inverse`](pymatgen.symmetry.md#pymatgen.symmetry.settings.JonesFaithfulTransformation.inverse)


            * [`JonesFaithfulTransformation.p`](pymatgen.symmetry.md#pymatgen.symmetry.settings.JonesFaithfulTransformation.p)


            * [`JonesFaithfulTransformation.parse_transformation_string()`](pymatgen.symmetry.md#pymatgen.symmetry.settings.JonesFaithfulTransformation.parse_transformation_string)


            * [`JonesFaithfulTransformation.transform_coords()`](pymatgen.symmetry.md#pymatgen.symmetry.settings.JonesFaithfulTransformation.transform_coords)


            * [`JonesFaithfulTransformation.transform_lattice()`](pymatgen.symmetry.md#pymatgen.symmetry.settings.JonesFaithfulTransformation.transform_lattice)


            * [`JonesFaithfulTransformation.transform_symmop()`](pymatgen.symmetry.md#pymatgen.symmetry.settings.JonesFaithfulTransformation.transform_symmop)


            * [`JonesFaithfulTransformation.transformation_string`](pymatgen.symmetry.md#pymatgen.symmetry.settings.JonesFaithfulTransformation.transformation_string)


    * [pymatgen.symmetry.site_symmetries module](pymatgen.symmetry.md#module-pymatgen.symmetry.site_symmetries)


        * [`get_shared_symmetry_operations()`](pymatgen.symmetry.md#pymatgen.symmetry.site_symmetries.get_shared_symmetry_operations)


        * [`get_site_symmetries()`](pymatgen.symmetry.md#pymatgen.symmetry.site_symmetries.get_site_symmetries)


    * [pymatgen.symmetry.structure module](pymatgen.symmetry.md#module-pymatgen.symmetry.structure)


        * [`SymmetrizedStructure`](pymatgen.symmetry.md#pymatgen.symmetry.structure.SymmetrizedStructure)


            * [`SymmetrizedStructure.equivalent_indices`](pymatgen.symmetry.md#pymatgen.symmetry.structure.SymmetrizedStructure.equivalent_indices)


            * [`SymmetrizedStructure._abc_impl`](pymatgen.symmetry.md#pymatgen.symmetry.structure.SymmetrizedStructure._abc_impl)


            * [`SymmetrizedStructure._properties`](pymatgen.symmetry.md#pymatgen.symmetry.structure.SymmetrizedStructure._properties)


            * [`SymmetrizedStructure._sites`](pymatgen.symmetry.md#pymatgen.symmetry.structure.SymmetrizedStructure._sites)


            * [`SymmetrizedStructure.as_dict()`](pymatgen.symmetry.md#pymatgen.symmetry.structure.SymmetrizedStructure.as_dict)


            * [`SymmetrizedStructure.copy()`](pymatgen.symmetry.md#pymatgen.symmetry.structure.SymmetrizedStructure.copy)


            * [`SymmetrizedStructure.find_equivalent_sites()`](pymatgen.symmetry.md#pymatgen.symmetry.structure.SymmetrizedStructure.find_equivalent_sites)


            * [`SymmetrizedStructure.from_dict()`](pymatgen.symmetry.md#pymatgen.symmetry.structure.SymmetrizedStructure.from_dict)


* [pymatgen.transformations package](pymatgen.transformations.md)




    * [pymatgen.transformations.advanced_transformations module](pymatgen.transformations.md#module-pymatgen.transformations.advanced_transformations)


        * [`AddAdsorbateTransformation`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.AddAdsorbateTransformation)


            * [`AddAdsorbateTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.AddAdsorbateTransformation._abc_impl)


            * [`AddAdsorbateTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.AddAdsorbateTransformation.apply_transformation)


            * [`AddAdsorbateTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.AddAdsorbateTransformation.inverse)


            * [`AddAdsorbateTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.AddAdsorbateTransformation.is_one_to_many)


        * [`ChargeBalanceTransformation`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.ChargeBalanceTransformation)


            * [`ChargeBalanceTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.ChargeBalanceTransformation._abc_impl)


            * [`ChargeBalanceTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.ChargeBalanceTransformation.apply_transformation)


            * [`ChargeBalanceTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.ChargeBalanceTransformation.inverse)


            * [`ChargeBalanceTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.ChargeBalanceTransformation.is_one_to_many)


        * [`CubicSupercellTransformation`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.CubicSupercellTransformation)


            * [`CubicSupercellTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.CubicSupercellTransformation._abc_impl)


            * [`CubicSupercellTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.CubicSupercellTransformation.apply_transformation)


            * [`CubicSupercellTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.CubicSupercellTransformation.inverse)


            * [`CubicSupercellTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.CubicSupercellTransformation.is_one_to_many)


        * [`DisorderOrderedTransformation`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.DisorderOrderedTransformation)


            * [`DisorderOrderedTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.DisorderOrderedTransformation._abc_impl)


            * [`DisorderOrderedTransformation._get_disorder_mappings()`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.DisorderOrderedTransformation._get_disorder_mappings)


            * [`DisorderOrderedTransformation._partition_species()`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.DisorderOrderedTransformation._partition_species)


            * [`DisorderOrderedTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.DisorderOrderedTransformation.apply_transformation)


            * [`DisorderOrderedTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.DisorderOrderedTransformation.inverse)


            * [`DisorderOrderedTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.DisorderOrderedTransformation.is_one_to_many)


        * [`DopingTransformation`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.DopingTransformation)


            * [`DopingTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.DopingTransformation._abc_impl)


            * [`DopingTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.DopingTransformation.apply_transformation)


            * [`DopingTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.DopingTransformation.inverse)


            * [`DopingTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.DopingTransformation.is_one_to_many)


        * [`EnumerateStructureTransformation`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.EnumerateStructureTransformation)


            * [`EnumerateStructureTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.EnumerateStructureTransformation._abc_impl)


            * [`EnumerateStructureTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.EnumerateStructureTransformation.apply_transformation)


            * [`EnumerateStructureTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.EnumerateStructureTransformation.inverse)


            * [`EnumerateStructureTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.EnumerateStructureTransformation.is_one_to_many)


        * [`GrainBoundaryTransformation`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.GrainBoundaryTransformation)


            * [`GrainBoundaryTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.GrainBoundaryTransformation._abc_impl)


            * [`GrainBoundaryTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.GrainBoundaryTransformation.apply_transformation)


            * [`GrainBoundaryTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.GrainBoundaryTransformation.inverse)


            * [`GrainBoundaryTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.GrainBoundaryTransformation.is_one_to_many)


        * [`MagOrderParameterConstraint`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.MagOrderParameterConstraint)


            * [`MagOrderParameterConstraint.satisfies_constraint()`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.MagOrderParameterConstraint.satisfies_constraint)


        * [`MagOrderingTransformation`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.MagOrderingTransformation)


            * [`MagOrderingTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.MagOrderingTransformation._abc_impl)


            * [`MagOrderingTransformation._add_dummy_species()`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.MagOrderingTransformation._add_dummy_species)


            * [`MagOrderingTransformation._add_spin_magnitudes()`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.MagOrderingTransformation._add_spin_magnitudes)


            * [`MagOrderingTransformation._remove_dummy_species()`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.MagOrderingTransformation._remove_dummy_species)


            * [`MagOrderingTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.MagOrderingTransformation.apply_transformation)


            * [`MagOrderingTransformation.determine_min_cell()`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.MagOrderingTransformation.determine_min_cell)


            * [`MagOrderingTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.MagOrderingTransformation.inverse)


            * [`MagOrderingTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.MagOrderingTransformation.is_one_to_many)


        * [`MonteCarloRattleTransformation`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.MonteCarloRattleTransformation)


            * [`MonteCarloRattleTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.MonteCarloRattleTransformation._abc_impl)


            * [`MonteCarloRattleTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.MonteCarloRattleTransformation.apply_transformation)


            * [`MonteCarloRattleTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.MonteCarloRattleTransformation.inverse)


            * [`MonteCarloRattleTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.MonteCarloRattleTransformation.is_one_to_many)


        * [`MultipleSubstitutionTransformation`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.MultipleSubstitutionTransformation)


            * [`MultipleSubstitutionTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.MultipleSubstitutionTransformation.apply_transformation)


            * [`MultipleSubstitutionTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.MultipleSubstitutionTransformation.inverse)


            * [`MultipleSubstitutionTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.MultipleSubstitutionTransformation.is_one_to_many)


        * [`SQSTransformation`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.SQSTransformation)


            * [`SQSTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.SQSTransformation._abc_impl)


            * [`SQSTransformation._get_disordered_substructure()`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.SQSTransformation._get_disordered_substructure)


            * [`SQSTransformation._get_max_neighbor_distance()`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.SQSTransformation._get_max_neighbor_distance)


            * [`SQSTransformation._get_unique_bestsqs_strucs()`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.SQSTransformation._get_unique_bestsqs_strucs)


            * [`SQSTransformation._sqs_cluster_estimate()`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.SQSTransformation._sqs_cluster_estimate)


            * [`SQSTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.SQSTransformation.apply_transformation)


            * [`SQSTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.SQSTransformation.inverse)


            * [`SQSTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.SQSTransformation.is_one_to_many)


        * [`SlabTransformation`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.SlabTransformation)


            * [`SlabTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.SlabTransformation._abc_impl)


            * [`SlabTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.SlabTransformation.apply_transformation)


            * [`SlabTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.SlabTransformation.inverse)


            * [`SlabTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.SlabTransformation.is_one_to_many)


        * [`SubstituteSurfaceSiteTransformation`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.SubstituteSurfaceSiteTransformation)


            * [`SubstituteSurfaceSiteTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.SubstituteSurfaceSiteTransformation._abc_impl)


            * [`SubstituteSurfaceSiteTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.SubstituteSurfaceSiteTransformation.apply_transformation)


            * [`SubstituteSurfaceSiteTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.SubstituteSurfaceSiteTransformation.inverse)


            * [`SubstituteSurfaceSiteTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.SubstituteSurfaceSiteTransformation.is_one_to_many)


        * [`SubstitutionPredictorTransformation`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.SubstitutionPredictorTransformation)


            * [`SubstitutionPredictorTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.SubstitutionPredictorTransformation._abc_impl)


            * [`SubstitutionPredictorTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.SubstitutionPredictorTransformation.apply_transformation)


            * [`SubstitutionPredictorTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.SubstitutionPredictorTransformation.inverse)


            * [`SubstitutionPredictorTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.SubstitutionPredictorTransformation.is_one_to_many)


        * [`SuperTransformation`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.SuperTransformation)


            * [`SuperTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.SuperTransformation._abc_impl)


            * [`SuperTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.SuperTransformation.apply_transformation)


            * [`SuperTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.SuperTransformation.inverse)


            * [`SuperTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations.SuperTransformation.is_one_to_many)


        * [`_find_codopant()`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations._find_codopant)


        * [`_proj()`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations._proj)


        * [`_round_and_make_arr_singular()`](pymatgen.transformations.md#pymatgen.transformations.advanced_transformations._round_and_make_arr_singular)


    * [pymatgen.transformations.site_transformations module](pymatgen.transformations.md#module-pymatgen.transformations.site_transformations)


        * [`AddSitePropertyTransformation`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.AddSitePropertyTransformation)


            * [`AddSitePropertyTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.AddSitePropertyTransformation._abc_impl)


            * [`AddSitePropertyTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.AddSitePropertyTransformation.apply_transformation)


            * [`AddSitePropertyTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.AddSitePropertyTransformation.inverse)


            * [`AddSitePropertyTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.AddSitePropertyTransformation.is_one_to_many)


        * [`InsertSitesTransformation`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.InsertSitesTransformation)


            * [`InsertSitesTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.InsertSitesTransformation._abc_impl)


            * [`InsertSitesTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.InsertSitesTransformation.apply_transformation)


            * [`InsertSitesTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.InsertSitesTransformation.inverse)


            * [`InsertSitesTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.InsertSitesTransformation.is_one_to_many)


        * [`PartialRemoveSitesTransformation`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.PartialRemoveSitesTransformation)


            * [`PartialRemoveSitesTransformation.ALGO_BEST_FIRST`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.PartialRemoveSitesTransformation.ALGO_BEST_FIRST)


            * [`PartialRemoveSitesTransformation.ALGO_COMPLETE`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.PartialRemoveSitesTransformation.ALGO_COMPLETE)


            * [`PartialRemoveSitesTransformation.ALGO_ENUMERATE`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.PartialRemoveSitesTransformation.ALGO_ENUMERATE)


            * [`PartialRemoveSitesTransformation.ALGO_FAST`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.PartialRemoveSitesTransformation.ALGO_FAST)


            * [`PartialRemoveSitesTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.PartialRemoveSitesTransformation._abc_impl)


            * [`PartialRemoveSitesTransformation._best_first_ordering()`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.PartialRemoveSitesTransformation._best_first_ordering)


            * [`PartialRemoveSitesTransformation._complete_ordering()`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.PartialRemoveSitesTransformation._complete_ordering)


            * [`PartialRemoveSitesTransformation._enumerate_ordering()`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.PartialRemoveSitesTransformation._enumerate_ordering)


            * [`PartialRemoveSitesTransformation._fast_ordering()`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.PartialRemoveSitesTransformation._fast_ordering)


            * [`PartialRemoveSitesTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.PartialRemoveSitesTransformation.apply_transformation)


            * [`PartialRemoveSitesTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.PartialRemoveSitesTransformation.inverse)


            * [`PartialRemoveSitesTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.PartialRemoveSitesTransformation.is_one_to_many)


        * [`RadialSiteDistortionTransformation`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.RadialSiteDistortionTransformation)


            * [`RadialSiteDistortionTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.RadialSiteDistortionTransformation._abc_impl)


            * [`RadialSiteDistortionTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.RadialSiteDistortionTransformation.apply_transformation)


            * [`RadialSiteDistortionTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.RadialSiteDistortionTransformation.inverse)


            * [`RadialSiteDistortionTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.RadialSiteDistortionTransformation.is_one_to_many)


            * [`RadialSiteDistortionTransformation.use_multiprocessing`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.RadialSiteDistortionTransformation.use_multiprocessing)


        * [`RemoveSitesTransformation`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.RemoveSitesTransformation)


            * [`RemoveSitesTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.RemoveSitesTransformation._abc_impl)


            * [`RemoveSitesTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.RemoveSitesTransformation.apply_transformation)


            * [`RemoveSitesTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.RemoveSitesTransformation.inverse)


            * [`RemoveSitesTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.RemoveSitesTransformation.is_one_to_many)


        * [`ReplaceSiteSpeciesTransformation`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.ReplaceSiteSpeciesTransformation)


            * [`ReplaceSiteSpeciesTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.ReplaceSiteSpeciesTransformation._abc_impl)


            * [`ReplaceSiteSpeciesTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.ReplaceSiteSpeciesTransformation.apply_transformation)


            * [`ReplaceSiteSpeciesTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.ReplaceSiteSpeciesTransformation.inverse)


            * [`ReplaceSiteSpeciesTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.ReplaceSiteSpeciesTransformation.is_one_to_many)


        * [`TranslateSitesTransformation`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.TranslateSitesTransformation)


            * [`TranslateSitesTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.TranslateSitesTransformation._abc_impl)


            * [`TranslateSitesTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.TranslateSitesTransformation.apply_transformation)


            * [`TranslateSitesTransformation.as_dict()`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.TranslateSitesTransformation.as_dict)


            * [`TranslateSitesTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.TranslateSitesTransformation.inverse)


            * [`TranslateSitesTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.site_transformations.TranslateSitesTransformation.is_one_to_many)


    * [pymatgen.transformations.standard_transformations module](pymatgen.transformations.md#module-pymatgen.transformations.standard_transformations)


        * [`AutoOxiStateDecorationTransformation`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.AutoOxiStateDecorationTransformation)


            * [`AutoOxiStateDecorationTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.AutoOxiStateDecorationTransformation._abc_impl)


            * [`AutoOxiStateDecorationTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.AutoOxiStateDecorationTransformation.apply_transformation)


            * [`AutoOxiStateDecorationTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.AutoOxiStateDecorationTransformation.inverse)


            * [`AutoOxiStateDecorationTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.AutoOxiStateDecorationTransformation.is_one_to_many)


        * [`ChargedCellTransformation`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.ChargedCellTransformation)


            * [`ChargedCellTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.ChargedCellTransformation._abc_impl)


            * [`ChargedCellTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.ChargedCellTransformation.apply_transformation)


            * [`ChargedCellTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.ChargedCellTransformation.inverse)


            * [`ChargedCellTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.ChargedCellTransformation.is_one_to_many)


        * [`ConventionalCellTransformation`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.ConventionalCellTransformation)


            * [`ConventionalCellTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.ConventionalCellTransformation._abc_impl)


            * [`ConventionalCellTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.ConventionalCellTransformation.apply_transformation)


            * [`ConventionalCellTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.ConventionalCellTransformation.inverse)


            * [`ConventionalCellTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.ConventionalCellTransformation.is_one_to_many)


        * [`DeformStructureTransformation`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.DeformStructureTransformation)


            * [`DeformStructureTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.DeformStructureTransformation._abc_impl)


            * [`DeformStructureTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.DeformStructureTransformation.apply_transformation)


            * [`DeformStructureTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.DeformStructureTransformation.inverse)


            * [`DeformStructureTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.DeformStructureTransformation.is_one_to_many)


        * [`DiscretizeOccupanciesTransformation`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.DiscretizeOccupanciesTransformation)


            * [`DiscretizeOccupanciesTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.DiscretizeOccupanciesTransformation._abc_impl)


            * [`DiscretizeOccupanciesTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.DiscretizeOccupanciesTransformation.apply_transformation)


            * [`DiscretizeOccupanciesTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.DiscretizeOccupanciesTransformation.inverse)


            * [`DiscretizeOccupanciesTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.DiscretizeOccupanciesTransformation.is_one_to_many)


        * [`OrderDisorderedStructureTransformation`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.OrderDisorderedStructureTransformation)


            * [`OrderDisorderedStructureTransformation.ALGO_BEST_FIRST`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.OrderDisorderedStructureTransformation.ALGO_BEST_FIRST)


            * [`OrderDisorderedStructureTransformation.ALGO_COMPLETE`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.OrderDisorderedStructureTransformation.ALGO_COMPLETE)


            * [`OrderDisorderedStructureTransformation.ALGO_FAST`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.OrderDisorderedStructureTransformation.ALGO_FAST)


            * [`OrderDisorderedStructureTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.OrderDisorderedStructureTransformation._abc_impl)


            * [`OrderDisorderedStructureTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.OrderDisorderedStructureTransformation.apply_transformation)


            * [`OrderDisorderedStructureTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.OrderDisorderedStructureTransformation.inverse)


            * [`OrderDisorderedStructureTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.OrderDisorderedStructureTransformation.is_one_to_many)


            * [`OrderDisorderedStructureTransformation.lowest_energy_structure`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.OrderDisorderedStructureTransformation.lowest_energy_structure)


        * [`OxidationStateDecorationTransformation`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.OxidationStateDecorationTransformation)


            * [`OxidationStateDecorationTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.OxidationStateDecorationTransformation._abc_impl)


            * [`OxidationStateDecorationTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.OxidationStateDecorationTransformation.apply_transformation)


            * [`OxidationStateDecorationTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.OxidationStateDecorationTransformation.inverse)


            * [`OxidationStateDecorationTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.OxidationStateDecorationTransformation.is_one_to_many)


        * [`OxidationStateRemovalTransformation`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.OxidationStateRemovalTransformation)


            * [`OxidationStateRemovalTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.OxidationStateRemovalTransformation._abc_impl)


            * [`OxidationStateRemovalTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.OxidationStateRemovalTransformation.apply_transformation)


            * [`OxidationStateRemovalTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.OxidationStateRemovalTransformation.inverse)


            * [`OxidationStateRemovalTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.OxidationStateRemovalTransformation.is_one_to_many)


        * [`PartialRemoveSpecieTransformation`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.PartialRemoveSpecieTransformation)


            * [`PartialRemoveSpecieTransformation.ALGO_BEST_FIRST`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.PartialRemoveSpecieTransformation.ALGO_BEST_FIRST)


            * [`PartialRemoveSpecieTransformation.ALGO_COMPLETE`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.PartialRemoveSpecieTransformation.ALGO_COMPLETE)


            * [`PartialRemoveSpecieTransformation.ALGO_ENUMERATE`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.PartialRemoveSpecieTransformation.ALGO_ENUMERATE)


            * [`PartialRemoveSpecieTransformation.ALGO_FAST`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.PartialRemoveSpecieTransformation.ALGO_FAST)


            * [`PartialRemoveSpecieTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.PartialRemoveSpecieTransformation._abc_impl)


            * [`PartialRemoveSpecieTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.PartialRemoveSpecieTransformation.apply_transformation)


            * [`PartialRemoveSpecieTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.PartialRemoveSpecieTransformation.inverse)


            * [`PartialRemoveSpecieTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.PartialRemoveSpecieTransformation.is_one_to_many)


        * [`PerturbStructureTransformation`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.PerturbStructureTransformation)


            * [`PerturbStructureTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.PerturbStructureTransformation._abc_impl)


            * [`PerturbStructureTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.PerturbStructureTransformation.apply_transformation)


            * [`PerturbStructureTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.PerturbStructureTransformation.inverse)


            * [`PerturbStructureTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.PerturbStructureTransformation.is_one_to_many)


        * [`PrimitiveCellTransformation`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.PrimitiveCellTransformation)


            * [`PrimitiveCellTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.PrimitiveCellTransformation._abc_impl)


            * [`PrimitiveCellTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.PrimitiveCellTransformation.apply_transformation)


            * [`PrimitiveCellTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.PrimitiveCellTransformation.inverse)


            * [`PrimitiveCellTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.PrimitiveCellTransformation.is_one_to_many)


        * [`RemoveSpeciesTransformation`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.RemoveSpeciesTransformation)


            * [`RemoveSpeciesTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.RemoveSpeciesTransformation._abc_impl)


            * [`RemoveSpeciesTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.RemoveSpeciesTransformation.apply_transformation)


            * [`RemoveSpeciesTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.RemoveSpeciesTransformation.inverse)


            * [`RemoveSpeciesTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.RemoveSpeciesTransformation.is_one_to_many)


        * [`RotationTransformation`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.RotationTransformation)


            * [`RotationTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.RotationTransformation._abc_impl)


            * [`RotationTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.RotationTransformation.apply_transformation)


            * [`RotationTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.RotationTransformation.inverse)


            * [`RotationTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.RotationTransformation.is_one_to_many)


        * [`ScaleToRelaxedTransformation`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.ScaleToRelaxedTransformation)


            * [`ScaleToRelaxedTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.ScaleToRelaxedTransformation._abc_impl)


            * [`ScaleToRelaxedTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.ScaleToRelaxedTransformation.apply_transformation)


            * [`ScaleToRelaxedTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.ScaleToRelaxedTransformation.inverse)


            * [`ScaleToRelaxedTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.ScaleToRelaxedTransformation.is_one_to_many)


        * [`SubstitutionTransformation`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.SubstitutionTransformation)


            * [`SubstitutionTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.SubstitutionTransformation._abc_impl)


            * [`SubstitutionTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.SubstitutionTransformation.apply_transformation)


            * [`SubstitutionTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.SubstitutionTransformation.inverse)


            * [`SubstitutionTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.SubstitutionTransformation.is_one_to_many)


        * [`SupercellTransformation`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.SupercellTransformation)


            * [`SupercellTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.SupercellTransformation._abc_impl)


            * [`SupercellTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.SupercellTransformation.apply_transformation)


            * [`SupercellTransformation.from_boundary_distance()`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.SupercellTransformation.from_boundary_distance)


            * [`SupercellTransformation.from_scaling_factors()`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.SupercellTransformation.from_scaling_factors)


            * [`SupercellTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.SupercellTransformation.inverse)


            * [`SupercellTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.standard_transformations.SupercellTransformation.is_one_to_many)


    * [pymatgen.transformations.transformation_abc module](pymatgen.transformations.md#module-pymatgen.transformations.transformation_abc)


        * [`AbstractTransformation`](pymatgen.transformations.md#pymatgen.transformations.transformation_abc.AbstractTransformation)


            * [`AbstractTransformation._abc_impl`](pymatgen.transformations.md#pymatgen.transformations.transformation_abc.AbstractTransformation._abc_impl)


            * [`AbstractTransformation.apply_transformation()`](pymatgen.transformations.md#pymatgen.transformations.transformation_abc.AbstractTransformation.apply_transformation)


            * [`AbstractTransformation.inverse`](pymatgen.transformations.md#pymatgen.transformations.transformation_abc.AbstractTransformation.inverse)


            * [`AbstractTransformation.is_one_to_many`](pymatgen.transformations.md#pymatgen.transformations.transformation_abc.AbstractTransformation.is_one_to_many)


            * [`AbstractTransformation.use_multiprocessing`](pymatgen.transformations.md#pymatgen.transformations.transformation_abc.AbstractTransformation.use_multiprocessing)


* [pymatgen.util package](pymatgen.util.md)




    * [pymatgen.util.convergence module](pymatgen.util.md#module-pymatgen.util.convergence)


        * [`SplineInputError`](pymatgen.util.md#pymatgen.util.convergence.SplineInputError)


        * [`determine_convergence()`](pymatgen.util.md#pymatgen.util.convergence.determine_convergence)


        * [`exponential()`](pymatgen.util.md#pymatgen.util.convergence.exponential)


        * [`extrapolate_reciprocal()`](pymatgen.util.md#pymatgen.util.convergence.extrapolate_reciprocal)


        * [`extrapolate_simple_reciprocal()`](pymatgen.util.md#pymatgen.util.convergence.extrapolate_simple_reciprocal)


        * [`get_derivatives()`](pymatgen.util.md#pymatgen.util.convergence.get_derivatives)


        * [`get_weights()`](pymatgen.util.md#pymatgen.util.convergence.get_weights)


        * [`id_generator()`](pymatgen.util.md#pymatgen.util.convergence.id_generator)


        * [`measure()`](pymatgen.util.md#pymatgen.util.convergence.measure)


        * [`multi_curve_fit()`](pymatgen.util.md#pymatgen.util.convergence.multi_curve_fit)


        * [`multi_reciprocal_extra()`](pymatgen.util.md#pymatgen.util.convergence.multi_reciprocal_extra)


        * [`p0_exponential()`](pymatgen.util.md#pymatgen.util.convergence.p0_exponential)


        * [`p0_reciprocal()`](pymatgen.util.md#pymatgen.util.convergence.p0_reciprocal)


        * [`p0_simple_2reciprocal()`](pymatgen.util.md#pymatgen.util.convergence.p0_simple_2reciprocal)


        * [`p0_simple_4reciprocal()`](pymatgen.util.md#pymatgen.util.convergence.p0_simple_4reciprocal)


        * [`p0_simple_5reciprocal()`](pymatgen.util.md#pymatgen.util.convergence.p0_simple_5reciprocal)


        * [`p0_simple_reciprocal()`](pymatgen.util.md#pymatgen.util.convergence.p0_simple_reciprocal)


        * [`p0_single_reciprocal()`](pymatgen.util.md#pymatgen.util.convergence.p0_single_reciprocal)


        * [`print_and_raise_error()`](pymatgen.util.md#pymatgen.util.convergence.print_and_raise_error)


        * [`print_plot_line()`](pymatgen.util.md#pymatgen.util.convergence.print_plot_line)


        * [`reciprocal()`](pymatgen.util.md#pymatgen.util.convergence.reciprocal)


        * [`simple_2reciprocal()`](pymatgen.util.md#pymatgen.util.convergence.simple_2reciprocal)


        * [`simple_4reciprocal()`](pymatgen.util.md#pymatgen.util.convergence.simple_4reciprocal)


        * [`simple_5reciprocal()`](pymatgen.util.md#pymatgen.util.convergence.simple_5reciprocal)


        * [`simple_reciprocal()`](pymatgen.util.md#pymatgen.util.convergence.simple_reciprocal)


        * [`single_reciprocal()`](pymatgen.util.md#pymatgen.util.convergence.single_reciprocal)


    * [pymatgen.util.coord module](pymatgen.util.md#module-pymatgen.util.coord)


        * [`Simplex`](pymatgen.util.md#pymatgen.util.coord.Simplex)


            * [`Simplex.space_dim`](pymatgen.util.md#pymatgen.util.coord.Simplex.space_dim)


            * [`Simplex.simplex_dim`](pymatgen.util.md#pymatgen.util.coord.Simplex.simplex_dim)


            * [`Simplex.bary_coords()`](pymatgen.util.md#pymatgen.util.coord.Simplex.bary_coords)


            * [`Simplex.coords`](pymatgen.util.md#pymatgen.util.coord.Simplex.coords)


            * [`Simplex.in_simplex()`](pymatgen.util.md#pymatgen.util.coord.Simplex.in_simplex)


            * [`Simplex.line_intersection()`](pymatgen.util.md#pymatgen.util.coord.Simplex.line_intersection)


            * [`Simplex.point_from_bary_coords()`](pymatgen.util.md#pymatgen.util.coord.Simplex.point_from_bary_coords)


            * [`Simplex.volume`](pymatgen.util.md#pymatgen.util.coord.Simplex.volume)


        * [`all_distances()`](pymatgen.util.md#pymatgen.util.coord.all_distances)


        * [`barycentric_coords()`](pymatgen.util.md#pymatgen.util.coord.barycentric_coords)


        * [`coord_list_mapping()`](pymatgen.util.md#pymatgen.util.coord.coord_list_mapping)


        * [`coord_list_mapping_pbc()`](pymatgen.util.md#pymatgen.util.coord.coord_list_mapping_pbc)


        * [`find_in_coord_list()`](pymatgen.util.md#pymatgen.util.coord.find_in_coord_list)


        * [`find_in_coord_list_pbc()`](pymatgen.util.md#pymatgen.util.coord.find_in_coord_list_pbc)


        * [`get_angle()`](pymatgen.util.md#pymatgen.util.coord.get_angle)


        * [`get_linear_interpolated_value()`](pymatgen.util.md#pymatgen.util.coord.get_linear_interpolated_value)


        * [`in_coord_list()`](pymatgen.util.md#pymatgen.util.coord.in_coord_list)


        * [`in_coord_list_pbc()`](pymatgen.util.md#pymatgen.util.coord.in_coord_list_pbc)


        * [`is_coord_subset()`](pymatgen.util.md#pymatgen.util.coord.is_coord_subset)


        * [`is_coord_subset_pbc()`](pymatgen.util.md#pymatgen.util.coord.is_coord_subset_pbc)


        * [`lattice_points_in_supercell()`](pymatgen.util.md#pymatgen.util.coord.lattice_points_in_supercell)


        * [`pbc_diff()`](pymatgen.util.md#pymatgen.util.coord.pbc_diff)


        * [`pbc_shortest_vectors()`](pymatgen.util.md#pymatgen.util.coord.pbc_shortest_vectors)


    * [pymatgen.util.coord_cython module](pymatgen.util.md#module-pymatgen.util.coord_cython)


        * [`coord_list_mapping_pbc()`](pymatgen.util.md#pymatgen.util.coord_cython.coord_list_mapping_pbc)


        * [`is_coord_subset_pbc()`](pymatgen.util.md#pymatgen.util.coord_cython.is_coord_subset_pbc)


        * [`pbc_shortest_vectors()`](pymatgen.util.md#pymatgen.util.coord_cython.pbc_shortest_vectors)


    * [pymatgen.util.due module](pymatgen.util.md#module-pymatgen.util.due)


        * [`BibTeX()`](pymatgen.util.md#pymatgen.util.due.BibTeX)


        * [`Doi()`](pymatgen.util.md#pymatgen.util.due.Doi)


        * [`InactiveDueCreditCollector`](pymatgen.util.md#pymatgen.util.due.InactiveDueCreditCollector)


            * [`InactiveDueCreditCollector._donothing()`](pymatgen.util.md#pymatgen.util.due.InactiveDueCreditCollector._donothing)


            * [`InactiveDueCreditCollector.activate()`](pymatgen.util.md#pymatgen.util.due.InactiveDueCreditCollector.activate)


            * [`InactiveDueCreditCollector.active`](pymatgen.util.md#pymatgen.util.due.InactiveDueCreditCollector.active)


            * [`InactiveDueCreditCollector.add()`](pymatgen.util.md#pymatgen.util.due.InactiveDueCreditCollector.add)


            * [`InactiveDueCreditCollector.cite()`](pymatgen.util.md#pymatgen.util.due.InactiveDueCreditCollector.cite)


            * [`InactiveDueCreditCollector.dcite()`](pymatgen.util.md#pymatgen.util.due.InactiveDueCreditCollector.dcite)


            * [`InactiveDueCreditCollector.dump()`](pymatgen.util.md#pymatgen.util.due.InactiveDueCreditCollector.dump)


            * [`InactiveDueCreditCollector.load()`](pymatgen.util.md#pymatgen.util.due.InactiveDueCreditCollector.load)


        * [`Text()`](pymatgen.util.md#pymatgen.util.due.Text)


        * [`Url()`](pymatgen.util.md#pymatgen.util.due.Url)


        * [`_donothing_func()`](pymatgen.util.md#pymatgen.util.due._donothing_func)


    * [pymatgen.util.graph_hashing module](pymatgen.util.md#module-pymatgen.util.graph_hashing)


        * [`_hash_label()`](pymatgen.util.md#pymatgen.util.graph_hashing._hash_label)


        * [`_init_node_labels()`](pymatgen.util.md#pymatgen.util.graph_hashing._init_node_labels)


        * [`_neighborhood_aggregate()`](pymatgen.util.md#pymatgen.util.graph_hashing._neighborhood_aggregate)


        * [`weisfeiler_lehman_graph_hash()`](pymatgen.util.md#pymatgen.util.graph_hashing.weisfeiler_lehman_graph_hash)


        * [`weisfeiler_lehman_subgraph_hashes()`](pymatgen.util.md#pymatgen.util.graph_hashing.weisfeiler_lehman_subgraph_hashes)


    * [pymatgen.util.io_utils module](pymatgen.util.md#module-pymatgen.util.io_utils)


        * [`clean_lines()`](pymatgen.util.md#pymatgen.util.io_utils.clean_lines)


        * [`micro_pyawk()`](pymatgen.util.md#pymatgen.util.io_utils.micro_pyawk)


    * [pymatgen.util.num module](pymatgen.util.md#module-pymatgen.util.num)


        * [`make_symmetric_matrix_from_upper_tri()`](pymatgen.util.md#pymatgen.util.num.make_symmetric_matrix_from_upper_tri)


        * [`round_to_sigfigs()`](pymatgen.util.md#pymatgen.util.num.round_to_sigfigs)


    * [pymatgen.util.numba module](pymatgen.util.md#module-pymatgen.util.numba)


        * [`jit()`](pymatgen.util.md#pymatgen.util.numba.jit)


        * [`njit()`](pymatgen.util.md#pymatgen.util.numba.njit)


    * [pymatgen.util.plotting module](pymatgen.util.md#module-pymatgen.util.plotting)


        * [`_decide_fontcolor()`](pymatgen.util.md#pymatgen.util.plotting._decide_fontcolor)


        * [`add_fig_kwargs()`](pymatgen.util.md#pymatgen.util.plotting.add_fig_kwargs)


        * [`format_formula()`](pymatgen.util.md#pymatgen.util.plotting.format_formula)


        * [`get_ax3d_fig()`](pymatgen.util.md#pymatgen.util.plotting.get_ax3d_fig)


        * [`get_ax_fig()`](pymatgen.util.md#pymatgen.util.plotting.get_ax_fig)


        * [`get_axarray_fig_plt()`](pymatgen.util.md#pymatgen.util.plotting.get_axarray_fig_plt)


        * [`periodic_table_heatmap()`](pymatgen.util.md#pymatgen.util.plotting.periodic_table_heatmap)


        * [`pretty_plot()`](pymatgen.util.md#pymatgen.util.plotting.pretty_plot)


        * [`pretty_plot_two_axis()`](pymatgen.util.md#pymatgen.util.plotting.pretty_plot_two_axis)


        * [`pretty_polyfit_plot()`](pymatgen.util.md#pymatgen.util.plotting.pretty_polyfit_plot)


        * [`van_arkel_triangle()`](pymatgen.util.md#pymatgen.util.plotting.van_arkel_triangle)


    * [pymatgen.util.provenance module](pymatgen.util.md#module-pymatgen.util.provenance)


        * [`Author`](pymatgen.util.md#pymatgen.util.provenance.Author)


            * [`Author.as_dict()`](pymatgen.util.md#pymatgen.util.provenance.Author.as_dict)


            * [`Author.from_dict()`](pymatgen.util.md#pymatgen.util.provenance.Author.from_dict)


            * [`Author.parse_author()`](pymatgen.util.md#pymatgen.util.provenance.Author.parse_author)


        * [`HistoryNode`](pymatgen.util.md#pymatgen.util.provenance.HistoryNode)


            * [`HistoryNode.name`](pymatgen.util.md#pymatgen.util.provenance.HistoryNode.name)


            * [`HistoryNode.url`](pymatgen.util.md#pymatgen.util.provenance.HistoryNode.url)


            * [`HistoryNode.description`](pymatgen.util.md#pymatgen.util.provenance.HistoryNode.description)


            * [`HistoryNode.as_dict()`](pymatgen.util.md#pymatgen.util.provenance.HistoryNode.as_dict)


            * [`HistoryNode.from_dict()`](pymatgen.util.md#pymatgen.util.provenance.HistoryNode.from_dict)


            * [`HistoryNode.parse_history_node()`](pymatgen.util.md#pymatgen.util.provenance.HistoryNode.parse_history_node)


        * [`StructureNL`](pymatgen.util.md#pymatgen.util.provenance.StructureNL)


            * [`StructureNL.as_dict()`](pymatgen.util.md#pymatgen.util.provenance.StructureNL.as_dict)


            * [`StructureNL.from_dict()`](pymatgen.util.md#pymatgen.util.provenance.StructureNL.from_dict)


            * [`StructureNL.from_structures()`](pymatgen.util.md#pymatgen.util.provenance.StructureNL.from_structures)


        * [`is_valid_bibtex()`](pymatgen.util.md#pymatgen.util.provenance.is_valid_bibtex)


    * [pymatgen.util.string module](pymatgen.util.md#module-pymatgen.util.string)


        * [`Stringify`](pymatgen.util.md#pymatgen.util.string.Stringify)


            * [`Stringify.STRING_MODE`](pymatgen.util.md#pymatgen.util.string.Stringify.STRING_MODE)


            * [`Stringify.to_html_string()`](pymatgen.util.md#pymatgen.util.string.Stringify.to_html_string)


            * [`Stringify.to_latex_string()`](pymatgen.util.md#pymatgen.util.string.Stringify.to_latex_string)


            * [`Stringify.to_pretty_string()`](pymatgen.util.md#pymatgen.util.string.Stringify.to_pretty_string)


            * [`Stringify.to_unicode_string()`](pymatgen.util.md#pymatgen.util.string.Stringify.to_unicode_string)


        * [`charge_string()`](pymatgen.util.md#pymatgen.util.string.charge_string)


        * [`disordered_formula()`](pymatgen.util.md#pymatgen.util.string.disordered_formula)


        * [`formula_double_format()`](pymatgen.util.md#pymatgen.util.string.formula_double_format)


        * [`htmlify()`](pymatgen.util.md#pymatgen.util.string.htmlify)


        * [`latexify()`](pymatgen.util.md#pymatgen.util.string.latexify)


        * [`latexify_spacegroup()`](pymatgen.util.md#pymatgen.util.string.latexify_spacegroup)


        * [`str_delimited()`](pymatgen.util.md#pymatgen.util.string.str_delimited)


        * [`stream_has_colors()`](pymatgen.util.md#pymatgen.util.string.stream_has_colors)


        * [`transformation_to_string()`](pymatgen.util.md#pymatgen.util.string.transformation_to_string)


        * [`unicodeify()`](pymatgen.util.md#pymatgen.util.string.unicodeify)


        * [`unicodeify_spacegroup()`](pymatgen.util.md#pymatgen.util.string.unicodeify_spacegroup)


        * [`unicodeify_species()`](pymatgen.util.md#pymatgen.util.string.unicodeify_species)


    * [pymatgen.util.testing module](pymatgen.util.md#module-pymatgen.util.testing)


        * [`PymatgenTest`](pymatgen.util.md#pymatgen.util.testing.PymatgenTest)


            * [`PymatgenTest.TEST_STRUCTURES`](pymatgen.util.md#pymatgen.util.testing.PymatgenTest.TEST_STRUCTURES)


            * [`PymatgenTest._multiprocess_shared_`](pymatgen.util.md#pymatgen.util.testing.PymatgenTest._multiprocess_shared_)


            * [`PymatgenTest._tmp_dir()`](pymatgen.util.md#pymatgen.util.testing.PymatgenTest._tmp_dir)


            * [`PymatgenTest.assert_msonable()`](pymatgen.util.md#pymatgen.util.testing.PymatgenTest.assert_msonable)


            * [`PymatgenTest.assert_str_content_equal()`](pymatgen.util.md#pymatgen.util.testing.PymatgenTest.assert_str_content_equal)


            * [`PymatgenTest.get_structure()`](pymatgen.util.md#pymatgen.util.testing.PymatgenTest.get_structure)


            * [`PymatgenTest.serialize_with_pickle()`](pymatgen.util.md#pymatgen.util.testing.PymatgenTest.serialize_with_pickle)


    * [pymatgen.util.typing module](pymatgen.util.md#module-pymatgen.util.typing)


* [pymatgen.vis package](pymatgen.vis.md)




    * [pymatgen.vis.plotters module](pymatgen.vis.md#module-pymatgen.vis.plotters)


        * [`SpectrumPlotter`](pymatgen.vis.md#pymatgen.vis.plotters.SpectrumPlotter)


            * [`SpectrumPlotter.add_spectra()`](pymatgen.vis.md#pymatgen.vis.plotters.SpectrumPlotter.add_spectra)


            * [`SpectrumPlotter.add_spectrum()`](pymatgen.vis.md#pymatgen.vis.plotters.SpectrumPlotter.add_spectrum)


            * [`SpectrumPlotter.get_plot()`](pymatgen.vis.md#pymatgen.vis.plotters.SpectrumPlotter.get_plot)


            * [`SpectrumPlotter.save_plot()`](pymatgen.vis.md#pymatgen.vis.plotters.SpectrumPlotter.save_plot)


            * [`SpectrumPlotter.show()`](pymatgen.vis.md#pymatgen.vis.plotters.SpectrumPlotter.show)


    * [pymatgen.vis.structure_chemview module](pymatgen.vis.md#module-pymatgen.vis.structure_chemview)


        * [`quick_view()`](pymatgen.vis.md#pymatgen.vis.structure_chemview.quick_view)


    * [pymatgen.vis.structure_vtk module](pymatgen.vis.md#module-pymatgen.vis.structure_vtk)


        * [`MultiStructuresInteractorStyle`](pymatgen.vis.md#pymatgen.vis.structure_vtk.MultiStructuresInteractorStyle)


            * [`MultiStructuresInteractorStyle.keyPressEvent()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.MultiStructuresInteractorStyle.keyPressEvent)


        * [`MultiStructuresVis`](pymatgen.vis.md#pymatgen.vis.structure_vtk.MultiStructuresVis)


            * [`MultiStructuresVis.DEFAULT_ANIMATED_MOVIE_OPTIONS`](pymatgen.vis.md#pymatgen.vis.structure_vtk.MultiStructuresVis.DEFAULT_ANIMATED_MOVIE_OPTIONS)


            * [`MultiStructuresVis.apply_tags()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.MultiStructuresVis.apply_tags)


            * [`MultiStructuresVis.display_help()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.MultiStructuresVis.display_help)


            * [`MultiStructuresVis.display_info()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.MultiStructuresVis.display_info)


            * [`MultiStructuresVis.display_warning()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.MultiStructuresVis.display_warning)


            * [`MultiStructuresVis.erase_info()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.MultiStructuresVis.erase_info)


            * [`MultiStructuresVis.erase_warning()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.MultiStructuresVis.erase_warning)


            * [`MultiStructuresVis.set_animated_movie_options()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.MultiStructuresVis.set_animated_movie_options)


            * [`MultiStructuresVis.set_structure()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.MultiStructuresVis.set_structure)


            * [`MultiStructuresVis.set_structures()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.MultiStructuresVis.set_structures)


        * [`StructureInteractorStyle`](pymatgen.vis.md#pymatgen.vis.structure_vtk.StructureInteractorStyle)


            * [`StructureInteractorStyle.keyPressEvent()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.StructureInteractorStyle.keyPressEvent)


            * [`StructureInteractorStyle.leftButtonPressEvent()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.StructureInteractorStyle.leftButtonPressEvent)


            * [`StructureInteractorStyle.leftButtonReleaseEvent()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.StructureInteractorStyle.leftButtonReleaseEvent)


            * [`StructureInteractorStyle.mouseMoveEvent()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.StructureInteractorStyle.mouseMoveEvent)


        * [`StructureVis`](pymatgen.vis.md#pymatgen.vis.structure_vtk.StructureVis)


            * [`StructureVis.add_bonds()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.StructureVis.add_bonds)


            * [`StructureVis.add_edges()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.StructureVis.add_edges)


            * [`StructureVis.add_faces()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.StructureVis.add_faces)


            * [`StructureVis.add_line()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.StructureVis.add_line)


            * [`StructureVis.add_partial_sphere()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.StructureVis.add_partial_sphere)


            * [`StructureVis.add_picker()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.StructureVis.add_picker)


            * [`StructureVis.add_picker_fixed()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.StructureVis.add_picker_fixed)


            * [`StructureVis.add_polyhedron()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.StructureVis.add_polyhedron)


            * [`StructureVis.add_site()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.StructureVis.add_site)


            * [`StructureVis.add_text()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.StructureVis.add_text)


            * [`StructureVis.add_triangle()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.StructureVis.add_triangle)


            * [`StructureVis.display_help()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.StructureVis.display_help)


            * [`StructureVis.orthongonalize_structure()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.StructureVis.orthongonalize_structure)


            * [`StructureVis.redraw()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.StructureVis.redraw)


            * [`StructureVis.rotate_view()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.StructureVis.rotate_view)


            * [`StructureVis.set_structure()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.StructureVis.set_structure)


            * [`StructureVis.show()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.StructureVis.show)


            * [`StructureVis.write_image()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.StructureVis.write_image)


            * [`StructureVis.zoom()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.StructureVis.zoom)


        * [`make_movie()`](pymatgen.vis.md#pymatgen.vis.structure_vtk.make_movie)



## pymatgen.dao module